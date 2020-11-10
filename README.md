
<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png" />

<h3 align="center">
  Desafio 10: GoRestaurant Web
</h3>

## :rocket: Sobre o desafio

O GoRestaurant é uma aplicação feita utilizando React.js junto com TypeScript, praticando o conceito de CRUD (Create, Read, Update, Delete).

Essa aplicação se conecta a uma fake API e exibe os pratos de comida criados e permite a criação, remoção e atualização desses pratos.

## :warning: Utilizando uma fake API

Antes de tudo, para que você tenha os dados para exibir em tela, criamos um arquivo que você poderá utilizar como fake API para te prover esses dados.

Para isso, deixamos instalado no seu package.json uma dependência chamada `json-server`, e um arquivo chamado `server.json`. Para executar esse servidor você pode executar o seguinte comando:

```js
  yarn json-server server.json -p 3333
```

## :trophy: Funcionalidades da aplicação

- **`Listar os pratos de comida da sua API`**: A página `Dashboard` exibe uma listagem com o campo `title`, `value`, e  `description` e `available` de todos os pratos de comida que estão cadastrados na sua API.

- **`Adicionar novos pratos de comida a sua API`**: Na página Dashboard, ao clicar no botão `Novo Prato` no Header, um modal é aberto. Esse modal é responsável por cadastrar uma nova `food` passando os campos `image`, `name`, `description`, `value`.

- **`Editar pratos de comida da sua API`**: Na página Dashboard, ao clicar no botão `Editar Prato`, um modal é aberto. Esse modal é responsável por editar uma `food` passando os campos `image`, `name`, `description`, `value`.

- **`Remover pratos de comida da sua API`**: Na página Dashboard é possível remover um prato de comida ao clicar no botão com ícone de lixeira no componente Food.

- **`Alterar disponibilidade dos pratos de comida da sua API`**: Na página Dashboard é possível alterar a disponibilidade de um prato de comida ao clicar no switch que é controlado pelo valor de `available`.


## :computer: Instruções de instalação e teste

Clone o repositório usando o `git` ou faça o download no formato zip. 
Antes de tudo, certifique-se de que você tem um gerenciador de pacotes (como o yarn) e o `Node.js` instalados em sua máquina.


Após baixar o projeto, abra uma aba do terminal e execute os seguintes comandos:

```Bash
# ../pasta-de-destino
$ cd gostack-gorestaurant-web
# ../pasta-de-destino/gostack-gorestaurant-web
$ yarn
```

Para iniciar a aplicação no localhost (porta 3000):

```Bash
# ../pasta-de-destino/gostack-gorestaurant-web
$ yarn start
```

Para rodar os testes da aplicação:
```Bash
# ../pasta-de-destino/gostack-gorestaurant-web
$ yarn test
```
