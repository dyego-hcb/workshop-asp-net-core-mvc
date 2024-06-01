# Projeto de Departamentos e Vendedoras - .NET MVC

Este é um projeto de aplicação web .NET MVC que gerencia departamentos e vendedoras. O sistema permite operações CRUD em vendedores e departamentos, além de fornecer funcionalidades de busca e agrupamento de registros de vendas.

## Funcionalidades

- **Detalhes do Vendedor e Carregamento Eager**: Visualização detalhada dos vendedores com informações do departamento associado.
- **Atualização do Vendedor e Exceções de Serviço Personalizadas**: Atualização de informações do vendedor com tratamento de exceções personalizado para não encontrados e conflitos de concorrência de banco de dados.
- **Página de Erro Personalizada**: Exibição de uma página de erro personalizada com informações detalhadas do erro.
- **Localização da Aplicação e Formatação de Números e Datas**: Configuração de localidade da aplicação para formatação adequada de números e datas.
- **Validação**: Anotações de validação em modelos para garantir a integridade dos dados.
- **Operações Assíncronas**: Melhoria de desempenho com operações assíncronas.
- **Tratamento de Exceções para Deleção**: Tratamento de exceções para integridade referencial ao deletar vendedores.
- **Navegação e Busca de Registros de Vendas**: Implementação de busca simples e agrupada de registros de vendas.

## Executar a Aplicação

Para executar o projeto localmente, siga estas etapas:

1. Clone o repositório.
2. Abra a solução no Visual Studio.
3. Configure a string de conexão no `appsettings.json`.
4. Execute as migrações do Entity Framework Core.
5. Inicie a aplicação.

---

# Departments and Saleswomen Project - .NET MVC

This is a .NET MVC web application project that manages departments and saleswomen. The system allows CRUD operations on sellers and departments, in addition to providing search and sales record grouping functionalities.

## Features

- **Seller Details and Eager Loading**: Detailed view of sellers with associated department information.
- **Seller Update and Custom Service Exceptions**: Seller information update with custom exception handling for not found and database concurrency conflicts.
- **Custom Error Page**: Display of a custom error page with detailed error information.
- **Application Localization and Number and Date Formatting**: Application locale configuration for proper number and date formatting.
- **Validation**: Validation annotations in models to ensure data integrity.
- **Asynchronous Operations**: Performance improvement with asynchronous operations.
- **Exception Handling for Deletion**: Exception handling for referential integrity when deleting sellers.
- **Sales Record Navigation and Search**: Implementation of simple and grouped search for sales records.

## Running the Application

To run the project locally, follow these steps:

1. Clone the repository.
2. Open the solution in Visual Studio.
3. Configure the connection string in `appsettings.json`.
4. Run the Entity Framework Core migrations.
5. Start the application.
