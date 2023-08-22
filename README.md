# Descrição do Projeto/Desafio

Este projeto é uma aplicação de banco de dados voltada para uma oficina "ficticia". A finalidade principal é gerenciar informações essenciais para a operação da oficina, incluindo detalhes dos clientes, veículos, ordens de serviço e status de manutenções. A estrutura é projetada de forma simples e intuitiva para facilitar o entendimento e a utilização.

**Tabelas:**

1. **Oficina**
   - Armazena informações sobre a oficina, como nome, endereço e telefone de contato.

2. **Cliente**
   - Contém os dados dos clientes da oficina, como nome, CPF e telefone.

3. **Veículo**
   - Registra os detalhes dos veículos dos clientes, como marca, modelo, ano e associação ao cliente correspondente.

4. **Ordem de Serviço**
   - Mantém o registro das ordens de serviço, incluindo data de abertura, descrição do problema, status atual e vínculos com cliente e veículo.

**Consultas Simples:**

1. **Listar Clientes:**
   - Recupera uma lista de todos os clientes cadastrados na oficina.

2. **Filtrar Veículos:**
   - Seleciona veículos de uma marca específica, permitindo visualizar os modelos disponíveis.

3. **Informações Combinadas:**
   - Apresenta uma tabela com nomes dos clientes e as marcas e modelos dos veículos associados a eles.

**Atributos Derivados:**

1. **Informações de Contato do Cliente:**
   - Combina o nome do cliente com seu telefone para gerar uma forma simples de contato.

**Ordenação de Dados:**

1. **Veículos por Ano:**
   - Exibe os veículos em ordem decrescente de ano, permitindo identificar os mais recentes.

**Filtros de Grupos:**

1. **Marcas Populares:**
   - Lista as marcas de veículos que têm mais de dois modelos registrados na oficina.

**Junções de Tabelas:**

1. **Relatório Cliente-Veículo:**
   - Combina informações de clientes e veículos, destacando quem possui quais veículos.

Este projeto oferece uma solução eficiente para a administração básica de uma oficina de manutenção veicular. Seu design minimalista e de fácil entendimento torna a gestão de clientes, veículos e ordens de serviço uma tarefa acessível para qualquer usuário.


## Description in english: 

This project is a database application designed for a "fictitious" workshop. Its main purpose is to manage essential information for the workshop's operation, including customer details, vehicles, service orders, and maintenance statuses. The structure is designed to be simple and intuitive for easy understanding and use.

**Tables:**

1. **Workshop**
   - Stores workshop information, such as name, address, and contact phone number.

2. **Customer**
   - Contains data about workshop customers, including name, CPF (ID), and phone number.

3. **Vehicle**
   - Records vehicle details, such as make, model, year, and association with the corresponding customer.

4. **Service Order**
   - Maintains records of service orders, including opening date, problem description, current status, and links to the associated customer and vehicle.

**Simple Queries:**

1. **List Customers:**
   - Retrieves a list of all customers registered with the workshop.

2. **Filter Vehicles:**
   - Selects vehicles of a specific make, allowing users to view available models.

3. **Combined Information:**
   - Presents a table with customer names and the makes and models of vehicles associated with them.

**Derived Attributes:**

1. **Customer Contact Information:**
   - Combines the customer's name with their phone number to provide an easy contact method.

**Data Sorting:**

1. **Vehicles by Year:**
   - Displays vehicles in descending order of year, enabling identification of the most recent ones.

**Group Filters:**

1. **Popular Makes:**
   - Lists vehicle makes that have more than two models registered in the workshop.

**Table Joins:**

1. **Customer-Vehicle Report:**
   - Combines customer and vehicle information, highlighting who owns which vehicles.

This project offers an efficient solution for basic administration of a vehicle maintenance workshop. Its minimalist and user-friendly design makes managing customers, vehicles, and service orders an accessible task for any user.
