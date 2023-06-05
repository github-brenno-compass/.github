# Compass Github

Olá, seja bem-vindo ao Compass Github Super App.

Este documento apresenta todos os repositórios disponíveis para desenvolvimento. Além disso, temos alguns padrões necessários para o desenvolvimento das features. Então, fique atento.

## Repositório

### Pull Request

Para fazer um Pull Request verifique se seu projeto está seguindo os padrões do Clean Code. Você também pode executar o `swiftlint lint` no seu terminal e corrigir qualquer erro encontrado.

### CI

Os PRs são validados por uma série de Actions implementadas:

1. Swiftlint
2. Build
3. Code coverage tests
4. Documentation **(Release only)**

### Testes

O projeto foi desenvolvido a partir de um Minimum Viable Project (MVP) que necessitou priorizar a integração do Super App em troca da implementação dos testes.

No entanto, a CI é capaz de acusar que os testes estão faltando e que é necessário implementá-los antes do PR ser aprovado.

> Testes de UI não foram pensados para esse projeto. Caso exista discussões futuras, seria interessante utilizar testes de UI baseados em snapshots.

## Features

O projeto está dividido nas seguintes features:

- [GithubKit](https://github.com/github-brenno-compass/GithubKit)
- [GithubUI](https://github.com/github-brenno-compass/GithubUI)
- [AuthenticationApp](https://github.com/github-brenno-compass/AuthenticationApp)
- [HomeApp](https://github.com/github-brenno-compass/HomeApp)