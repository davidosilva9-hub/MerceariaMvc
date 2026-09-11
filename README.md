# 🛒 MerceariaMVC

Sistema de gerenciamento de clientes desenvolvido utilizando **ASP.NET Core MVC**, com foco na aplicação de **TDD (Test Driven Development)** e testes automatizados utilizando **xUnit**.

O projeto foi desenvolvido como uma aplicação CRUD, permitindo realizar o cadastro, visualização, edição e exclusão de clientes.

---

## 📋 Sobre o Projeto

O **MerceariaMVC** é um sistema desenvolvido para praticar conceitos de desenvolvimento web com **C# e ASP.NET Core MVC**, além da utilização de testes automatizados durante o desenvolvimento.

A aplicação possui um CRUD de clientes, permitindo gerenciar informações como:

* 👤 Nome
* 📧 E-mail
* 🎂 Idade
* ✅ Status do cliente

* ## 📸 Demonstração do Sistema

### 🔍 Tela Inicial
<img width="1918" height="945" alt="Tela inicial" src="https://github.com/user-attachments/assets/b5549376-eb80-4f39-b1e0-10fa00c4da17" />

### 👥 Tela Clientes

<img width="1919" height="944" alt="Tela Clientes" src="https://github.com/user-attachments/assets/9d7da743-ff85-4c4b-a6b0-eaee6bb81ace" />


### 🥇 Novo Cliente

<img width="1872" height="932" alt="Novo CLiente" src="https://github.com/user-attachments/assets/d84ed76a-68f5-48c0-beba-d4a0e6b2924b" />



Além da aplicação principal, o projeto possui um projeto separado para os testes automatizados.

---

## 🧪 TDD e xUnit

Durante o desenvolvimento foi utilizada a metodologia **TDD (Test Driven Development)**, seguindo o conceito de desenvolver os testes antes da implementação da funcionalidade.

O projeto utiliza o **xUnit** para criação e execução dos testes automatizados.

A solução possui dois projetos principais:

```text
MerceariaMVC
│
├── MerceariaMVC
│   └── Aplicação principal
│
└── MerceariaMVCTests
    └── Testes automatizados
```

---

## 🚀 Funcionalidades

### 👥 Clientes

* [x] Cadastrar cliente
* [x] Listar clientes
* [x] Visualizar detalhes
* [x] Editar cliente
* [x] Excluir cliente
* [x] Validar informações
* [x] Testes automatizados

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia                | Utilização                       |
| ------------------------- | -------------------------------- |
| **C#**                    | Linguagem de programação         |
| **ASP.NET Core MVC**      | Desenvolvimento da aplicação web |
| **Entity Framework Core** | Acesso e gerenciamento de dados  |
| **SQL Server**            | Banco de dados                   |
| **HTML**                  | Estrutura das páginas            |
| **CSS**                   | Estilização da aplicação         |
| **Bootstrap**             | Interface e componentes visuais  |
| **xUnit**                 | Testes automatizados             |
| **TDD**                   | Metodologia de desenvolvimento   |

---

## 📂 Estrutura do Projeto

```text
MerceariaMVC
│
├── Controllers
│   └── ClienteController.cs
│
├── Models
│   └── Cliente.cs
│
├── Views
│   ├── Cliente
│   │   ├── Create.cshtml
│   │   ├── Delete.cshtml
│   │   ├── Details.cshtml
│   │   ├── Edit.cshtml
│   │   └── Index.cshtml
│   │
│   └── Shared
│       └── _Layout.cshtml
│
├── wwwroot
│   └── css
│       └── site.css
│
└── MerceariaMVCTests
    └── Testes automatizados
```

---

## ▶️ Como Executar

### 1. Clone o repositório

```bash
git clone URL_DO_REPOSITORIO
```

### 2. Abra o projeto

Abra o arquivo:

```text
MerceariaMVC.sln
```

utilizando o **Visual Studio**.

### 3. Configure o banco de dados

Verifique a string de conexão do projeto e configure o **SQL Server** de acordo com o seu ambiente.

### 4. Execute as migrations

Caso o projeto utilize migrations, execute:

```bash
Update-Database
```

### 5. Execute a aplicação

Pressione:

```text
F5
```

ou utilize o botão **▶️ Iniciar** no Visual Studio.

---

## 🧪 Executando os Testes

Para executar os testes pelo Visual Studio:

1. Abra o **Test Explorer**
2. Localize o projeto `MerceariaMVCTests`
3. Clique em **Run All Tests**

Também é possível executar pelo terminal:

```bash
dotnet test
```

Os testes têm como objetivo verificar se as regras e funcionalidades da aplicação estão funcionando corretamente.

---

## 🎨 Interface

A aplicação possui uma interface personalizada para facilitar a utilização do sistema.

Entre os elementos visuais estão:

* 🟢 Tema inspirado em mercearias
* 📋 Tabelas estilizadas
* 🟡 Botões de edição
* 🔵 Botões de detalhes
* 🔴 Botões de exclusão
* 📱 Layout responsivo
* ✨ Efeitos de interação

---

## 🎯 Objetivo

O principal objetivo do projeto é aplicar na prática conceitos de:

* Desenvolvimento Web
* C# e ASP.NET Core MVC
* Arquitetura MVC
* CRUD
* Banco de dados
* Testes automatizados
* TDD
* xUnit
* Validação de regras de negócio

---

## 👨‍💻 Autor

**David Oliveira**

GitHub:
[github.com/davidosilva9-hub](https://github.com/davidosilva9-hub?utm_source=chatgpt.com)

---

## 📌 Projeto Acadêmico

Projeto desenvolvido para fins de aprendizado e prática de desenvolvimento de sistemas utilizando **C#, ASP.NET Core MVC, TDD e xUnit**.
