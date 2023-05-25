# Cadastro de Clientes

Este repositório contém um projeto de cadastro de clientes, onde é possível inserir dados de clientes em um banco de dados e visualizar a listagem dos clientes cadastrados.

# Ferramentas Utilizadas:

O projeto utiliza as seguintes ferramentas:

HTML: Linguagem de marcação utilizada para construir a interface do formulário de cadastro e a tabela de listagem de clientes.

CSS: Folhas de estilo utilizadas para estilizar a interface do projeto.

Bootstrap: Framework CSS utilizado para fornecer estilos pré-definidos e facilitar o desenvolvimento responsivo.

PHP: Linguagem de programação utilizada para realizar a validação dos dados do formulário e a interação com o banco de dados.

PDO (PHP Data Objects): Extensão do PHP utilizada para a conexão e manipulação do banco de dados PostgreSQL.

PostgreSQL: Sistema de gerenciamento de banco de dados utilizado para armazenar os dados dos clientes.

# Funcionalidades:

O projeto possui as seguintes funcionalidades:

Validação dos dados do formulário de cadastro:

Verifica se o campo "Nome" não está vazio.

Verifica se o campo "CPF" possui 11 caracteres.

Verifica se o campo "E-mail" possui um formato válido.

Verifica se o campo "Data de Nascimento" não está vazio.

Conexão com o banco de dados:

Estabelece a conexão com o banco de dados PostgreSQL utilizando as constantes de configuração.

Inserção dos dados no banco de dados:

Realiza a inserção dos dados do cliente na tabela "cliente" do banco de dados.

Listagem dos clientes cadastrados:

Recupera os dados dos clientes cadastrados na tabela "cliente" do banco de dados e exibe-os em uma tabela na página.

# Utilização:

Para utilizar o projeto, siga as seguintes etapas:

Clone o repositório em sua máquina local.

Certifique-se de ter um servidor web configurado com suporte a PHP e PostgreSQL.

Importe o banco de dados "minimundo.sql" para o seu servidor PostgreSQL.

Configure as constantes de conexão com o banco de dados no arquivo PHP.

Execute o projeto através do servidor web.

Acesse a página no navegador e utilize o formulário para cadastrar clientes e visualizar a listagem.

Observação: Certifique-se de ter as dependências do Bootstrap e jQuery (incluídas nos links fornecidos) para que a interface funcione corretamente.

![Screenshot_22](https://github.com/TiagoMuller/Code_FormularioSQL/assets/39675368/b086917c-69ba-406d-96c4-466f8bba010c)

-------------------------------------

# Customer Registration

This repository contains a customer registration project where you can enter customer data into a database and view the list of registered customers.

# Tools Used:

The project utilizes the following tools:

HTML: Markup language used to build the registration form interface and the customer listing table.

CSS: Style sheets used to style the project interface.

Bootstrap: CSS framework used to provide pre-defined styles and facilitate responsive development.

PHP: Programming language used to perform form data validation and interact with the database.

PDO (PHP Data Objects): PHP extension used for connecting to and manipulating the PostgreSQL database.

PostgreSQL: Database management system used to store customer data.

# Features:

The project has the following features:

Form data validation:

Checks if the "Name" field is not empty.

Checks if the "CPF" field has 11 characters.

Checks if the "Email" field has a valid format.

Checks if the "Date of Birth" field is not empty.

Database connection:

Establishes a connection to the PostgreSQL database using the configuration constants.

Insertion of data into the database:

Inserts customer data into the "customer" table of the database.

Listing of registered customers:

Retrieves customer data from the "customer" table in the database and displays it in a table on the page.

# Usage:

To use the project, follow these steps:

Clone the repository to your local machine.

Make sure you have a web server configured with PHP and PostgreSQL support.

Import the "minimundo.sql" database into your PostgreSQL server.

Configure the database connection constants in the PHP file.

Run the project through the web server.

Access the page in your browser and use the form to register customers and view the listing.

Note: Make sure to have the Bootstrap and jQuery dependencies (included in the provided links) for the interface to function correctly.
