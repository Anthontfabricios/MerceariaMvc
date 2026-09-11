# 🛍️ Mercado+

## 📌 Sobre o Projeto

O **Mercado+** é um sistema de gerenciamento de uma mercearia desenvolvido utilizando a arquitetura **MVC (Model-View-Controller)**.

O sistema foi criado com o objetivo de facilitar o cadastro e o gerenciamento de **produtos e clientes**, proporcionando uma interface simples, organizada e fácil de utilizar.

---

## 🚀 Tecnologias Utilizadas

* C#
* ASP.NET Core MVC
* HTML5
* CSS3
* Bootstrap
* Entity Framework Core
* SQL Server
* Razor
* .NET

---

## 🎯 Objetivo

O objetivo do projeto é desenvolver um sistema para auxiliar no gerenciamento de uma mercearia, permitindo organizar informações de produtos e clientes de maneira prática.

---

## ⚙️ Funcionalidades

### 📦 Produtos

* Cadastrar produtos
* Visualizar produtos cadastrados
* Editar produtos
* Excluir produtos
* Consultar informações dos produtos

### 👤 Clientes

* Cadastrar clientes
* Visualizar clientes cadastrados
* Editar clientes
* Excluir clientes
* Consultar informações dos clientes

### 🏠 Página Inicial

* Apresentação do sistema
* Menu de navegação
* Acesso rápido às principais funcionalidades

---

## 🏗️ Arquitetura MVC

O projeto utiliza o padrão **MVC**, dividido em três partes principais:

### Model

Responsável pela representação dos dados e pelas regras relacionadas às entidades do sistema.

### View

Responsável pela interface que o usuário visualiza e utiliza.

### Controller

Responsável por receber as requisições, processar as informações e conectar os Models às Views.

---

## 📂 Estrutura do Projeto

```text
MercadoPlus/
│
├── Controllers/
│   ├── HomeController.cs
│   ├── ProdutoController.cs
│   └── ClienteController.cs
│
├── Models/
│   ├── Produto.cs
│   ├── Cliente.cs
│   └── ErrorViewModel.cs
│
├── Views/
│   ├── Home/
│   ├── Produto/
│   ├── Cliente/
│   └── Shared/
│
├── wwwroot/
│   ├── css/
│   ├── js/
│   └── lib/
│
├── Data/
│   └── Banco de dados
│
├── Program.cs
├── appsettings.json
└── README.md
```

---

## 🎨 Interface

A interface foi estilizada utilizando **CSS3 e Bootstrap**, buscando criar um sistema moderno, organizado e responsivo.

O layout possui:

* Menu de navegação
* Botões personalizados
* Tabelas organizadas
* Formulários estilizados
* Cards
* Design responsivo
* Cores e elementos visuais personalizados

---

## 🗄️ Banco de Dados

O projeto utiliza o **Entity Framework Core** para comunicação com o banco de dados.

As informações cadastradas pelo sistema são armazenadas de forma estruturada, permitindo realizar operações de:

* Inserção
* Consulta
* Alteração
* Exclusão

Essas operações são conhecidas como **CRUD**.

---

## 🔄 CRUD

O sistema utiliza as quatro operações básicas:

| Operação | Função                |
| -------- | --------------------- |
| Create   | Cadastrar novos dados |
| Read     | Consultar dados       |
| Update   | Alterar dados         |
| Delete   | Excluir dados         |

---

## ▶️ Como Executar o Projeto

### 1. Instale o .NET

Tenha o **.NET SDK** instalado no computador.

### 2. Abra o projeto

Abra a pasta do projeto no **Visual Studio** ou **Visual Studio Code**.

### 3. Configure o banco de dados

Verifique a string de conexão no arquivo:

```text
appsettings.json
```

### 4. Execute as migrations

No terminal, utilize:

```bash
dotnet ef database update
```

### 5. Execute o projeto

Utilize:

```bash
dotnet run
```

Depois, abra o endereço informado pelo terminal no navegador.

---

## 📚 Aprendizados

Durante o desenvolvimento do projeto foram trabalhados conhecimentos de:

* Programação em C#
* ASP.NET Core MVC
* Desenvolvimento Web
* HTML e CSS
* Bootstrap
* Entity Framework Core
* Banco de dados
* CRUD
* Arquitetura MVC
* Organização de projetos

---

## 👨‍💻 Projeto Acadêmico

Este projeto foi desenvolvido com finalidade **educacional**, servindo como prática para o desenvolvimento de aplicações Web utilizando **ASP.NET Core MVC**.

---

## 📄 Licença

Projeto desenvolvido para fins acadêmicos e de aprendizado.

AUTOR ANTHONY FABRICIO SANTANA SILVA 
