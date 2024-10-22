# Projeto API de Receitas

Este projeto consiste no desenvolvimento de uma API de receitas utilizando ASP.NET. A API permite operações CRUD (criar, ler, atualizar e deletar) para receitas e usuários, além de permitir o cadastro e consulta de comentários nas receitas.

## Funcionalidades

- Retornar todas as receitas disponíveis.
- Adicionar, remover e atualizar receitas.
- Cadastrar, remover, consultar e atualizar usuários.
- Cadastrar e consultar comentários nas receitas.
- A API possui documentação via **Swagger**.

## Pré-requisitos

Antes de começar, certifique-se de ter o seguinte instalado:

- [.NET SDK 6.0 ou superior](https://dotnet.microsoft.com/download)

## Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/arturpeixoto/projeto-api-de-receitas-csharp.git
```

### 2. Acesse o diretório do projeto

```bash
cd projeto-api-de-receitas-csharp
```

### 3. Restaure as dependências

Execute o comando para restaurar os pacotes necessários:

```bash
dotnet restore
```

## Execução

Para rodar a aplicação, utilize o comando:

```bash
dotnet run --project src/projeto-api-de-receitas-csharp
```

Ao executar o projeto, a API será documentada e acessível via **Swagger**. Após a execução, abra o navegador e acesse a URL exibida nos logs para visualizar a documentação da API e testar os endpoints.

## Como usar

A API oferece uma interface gráfica via Swagger, onde você pode interagir com os endpoints disponíveis, como criar, listar, atualizar e remover receitas, usuários e comentários.

## Tecnologias Utilizadas

- C#
- ASP.NET Core
- Swagger para documentação

## Contribuição

Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.
