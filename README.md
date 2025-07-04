# Petfolio

Petfolio é uma solução desenvolvida em .NET 8 para gerenciamento de informações relacionadas a pets. O projeto segue uma arquitetura modular, separando responsabilidades em diferentes camadas para facilitar manutenção, testes e escalabilidade.

## Projetos na Solução

- **Petfolio.API**: API principal baseada em ASP.NET Core, responsável por expor os endpoints REST.
- **Petfolio.Application**: Camada de aplicação, onde ficam as regras de negócio.
- **Petfolio.Communication**: Responsável pelos contratos de comunicação (DTOs, mensagens, etc).

## Principais Tecnologias

- [.NET 8](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- ASP.NET Core Web API
- [Swashbuckle.AspNetCore (Swagger)](https://github.com/domaindrivendev/Swashbuckle.AspNetCore) para documentação interativa da API

## Como Executar

1. **Pré-requisitos**:
   - [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) instalado

2. **Clonar o repositório**:
