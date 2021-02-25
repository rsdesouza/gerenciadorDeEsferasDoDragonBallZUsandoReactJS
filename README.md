# Criando um gerenciador de esferas do Dragon BallZ usando ReactJS, Jest, React Testing Library e Cypress

# O problema

You want to use [jest][] to write tests that assert various things about the
state of a DOM. As part of that goal, you want to avoid all the repetitive
patterns that arise in doing so. Checking for an element's attributes, its text
content, its css classes, you name it.

## Esta solução

Você deseja usar [jest] [] para escrever testes que afirmam várias coisas sobre o
estado de um DOM. Como parte dessa meta, você deseja evitar todos os processos repetitivos
padrões que surgem ao fazer isso. Verificando os atributos de um elemento, seu texto
conteúdo, suas classes css, você escolhe.

## Índice

<! - INICIE o TOC gerado pelo doctoc, por favor, mantenha os comentários aqui para permitir a atualização automática ->
<! - NÃO EDITE ESTA SEÇÃO, EM VEZ DE RE-EXECUTAR doctoc PARA ATUALIZAR ->


- [Installation](#installation)
- [Usage](#usage)
- [Custom matchers](#custom-matchers)
  - [`toBeDisabled`](#tobedisabled)
  - [`toBeEnabled`](#tobeenabled)
  - [`toBeEmpty`](#tobeempty)
  - [`toBeInTheDocument`](#tobeinthedocument)
  - [`toBeInvalid`](#tobeinvalid)
  - [`toBeRequired`](#toberequired)
  - [`toBeValid`](#tobevalid)
  - [`toBeVisible`](#tobevisible)
  - [`toContainElement`](#tocontainelement)
  - [`toContainHTML`](#tocontainhtml)
  - [`toHaveAttribute`](#tohaveattribute)
  - [`toHaveClass`](#tohaveclass)
  - [`toHaveFocus`](#tohavefocus)
  - [`toHaveFormValues`](#tohaveformvalues)
  - [`toHaveStyle`](#tohavestyle)
  - [`toHaveTextContent`](#tohavetextcontent)
  - [`toHaveValue`](#tohavevalue)
  - [`toHaveDisplayValue`](#tohavedisplayvalue)
  - [`toBeChecked`](#tobechecked)
  - [`toHaveDescription`](#tohavedescription)
- [Deprecated matchers](#deprecated-matchers)
  - [`toBeInTheDOM`](#tobeinthedom)
- [Inspiration](#inspiration)
- [Other Solutions](#other-solutions)
- [Guiding Principles](#guiding-principles)
- [Contributors](#contributors)
- [LICENSE](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Instalação


Este módulo é distribuído via [npm] [npm] que é empacotado com [nó] [nó] e
deve ser instalado como uma das `devDependencies` do seu projeto:

## Uso

Import `@testing-library/jest-dom` 
uma vez (for instance in your [tests setup
file][]) 
e você está pronto para ir:

[tests setup file]:
  https://jestjs.io/docs/en/configuration.html#setupfilesafterenv-array

