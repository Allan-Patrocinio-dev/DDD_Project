# DDD Project

Aplicação de e-commerce desenvolvida em C# e ASP.NET Core para praticar Domain-Driven Design, separação de responsabilidades e persistência de dados.

## Arquitetura

- `Entities`: entidades e regras centrais do domínio.
- `Domain`: serviços e interfaces de negócio.
- `Application`: casos de uso e coordenação da aplicação.
- `Infra`: repositórios, contexto de dados e migrations.
- `Presentation`: API e configuração da aplicação.
- `Web_ECommerce`: interface web para gerenciamento de produtos.

## Tecnologias

- C# e .NET
- ASP.NET Core
- Entity Framework Core
- SQL
- HTML, CSS e JavaScript

## Objetivo

O projeto demonstra a organização de uma aplicação em camadas, com foco em código manutenível, baixo acoplamento e evolução independente das responsabilidades.

## Como executar

1. Configure a string de conexão nos arquivos `appsettings.json`.
2. Restaure as dependências com `dotnet restore`.
3. Aplique as migrations com `dotnet ef database update`.
4. Execute a aplicação com `dotnet run` no projeto desejado.

> Projeto de estudo em evolução.
