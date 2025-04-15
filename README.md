# Sistema de Registro de Usuários com PHP - Programação III

- Criado por: Samuel De Lorenzi Ribeiro
- Turma: Ciência da Computação - Campus Videira

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

## 🚀 Requisitos e Dependências

- PHP: Versão 8.4.1 ou superior (versões mais antigas podem funcionar, porém não foram testadas).

- Servidor Web: Apache.

- Extensões PHP: Session e hash.

- Navegador: Qualquer navegador moderno.

## 📃 Instruções de Instalação

### Clonar o Repositório:
Clone o projeto para o seu ambiente local:

```bash
git clone https://github.com/samueldelorenzi/prog3-a1-poo-samueldelorenzi
```

### Configuração do Servidor:
Configure seu ambiente de desenvolvimento para apontar para a pasta raiz do projeto.

### Permissões:
Verifique se a pasta possui as permissões corretas para escrita e leitura.

## 📈 Utilização
Por fim basta acessar ```http://localhost/prog3-a1-poo-samueldelorenzi/``` no navegador e utilizar os botões para navegar pelas páginas.
