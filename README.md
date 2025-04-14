# Sistema de Registro de Usuários com PHP - Programação III

Projeto desenvolvido para a disciplina de **Programação III** do curso de **Ciência da Computação - UNOESC**, orientado pelo professor **Leandro Otavio Cordova Vieira**.

## 👨‍💻 Descrição

Este projeto consiste em uma aplicação web simples desenvolvida com **PHP puro**, utilizando os princípios da **Programação Orientada a Objetos (POO)**. O sistema permite o **cadastro e autenticação de usuários**, com uso de **sessões e cookies**, seguindo boas práticas de organização de código e segurança básica.

## 🔒 Funcionalidades

- Cadastro de usuários com nome, e-mail e senha
- Validação e sanitização de dados
- Autenticação com verificação de e-mail e senha
- Hash de senhas com `password_hash()` e verificação com `password_verify()`
- Login persistente com uso opcional de cookie para lembrar o e-mail
- Dashboard com saudação personalizada e exibição de informações do usuário
- Logout com destruição da sessão

## 📁 Estrutura de Diretórios
```
.
├── assets
│   └── favicon.ico
├── auxiliares.php
├── cadastro.php
├── classes
│   ├── Autenticador.php
│   ├── Sessao.php
│   └── Usuario.php
├── dashboard.php
├── index.php
├── login.php
├── logout.php
├── processa_cadastro.php
├── processa_login.php
└── style
    └── style.css
```
