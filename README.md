<h1 align="center">
    <img alt="Ignite" title="Ignite" src=".github/ignite.png" />
</h1>

<h2 align="center"> FinAPI - Financeira </h2>

</br>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Regras de Negócio</a>
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com/pt-br/)

## 📦 Projeto

Essa API tem como proposito realizar cadastro pelo CPF e nome de um usuário, fazer depósitos, saques, consultas, balanço e exclusão de uma conta.

## 🔵 Requisitos

- Deve ser possível criar uma conta
- Deve ser possível buscar o extrato bancário do cliente
- Deve ser possível realizar um saque
- Deve ser possível buscar o extrato bancário do cliente por data
- Deve ser possível atualizar dados da conta do cliente
- Deve ser possível obter dados da conta do cliente
- Deve ser possível deletar conta

## 🔴 Regras de Negócio

- Não deve ser possível cadastrar uma conta com CPF já existente
- Não deve ser possível fazer depósito em uma conta não existente
- Não deve ser possível buscar extrato em uma conta não existente
- Não deve ser possível fazer saque em uma conta não existente
- Não deve ser possível excluir uma conta não existente
- Não deve ser possível fazer saque quando o saldo for insuficiente 