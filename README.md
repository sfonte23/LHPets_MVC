# Projeto Web LH Pet (MVC)

Este projeto é um sistema de controle interno para a LH Pet, desenvolvido utilizando a arquitetura MVC (Model-View-Controller) em ASP.NET Core. O sistema permite gerenciar informações de clientes e fornecedores de forma eficiente e intuitiva.

## Descrição do Projeto

O sistema apresenta uma interface web amigável, onde os usuários podem visualizar listas de clientes e fornecedores, permitindo um controle mais organizado e acessível das informações.

### Funcionalidades

- **Listagem de Clientes**: Apresenta uma tabela com detalhes dos clientes cadastrados, incluindo ID, nome, CPF, e informações sobre o pet.
- **Listagem de Fornecedores**: Exibe uma tabela com dados dos fornecedores, incluindo ID, nome, CNPJ e e-mail.


### Detalhes dos Arquivos

- **program.cs**: Configura o pipeline de requisições e serviços do ASP.NET Core, definindo o controlador padrão e habilitando recursos como HTTPS e arquivos estáticos.

- **HomeController.cs**: Controlador responsável pela lógica de apresentação das listas de clientes e fornecedores. Inicializa os dados necessários e os passa para a view.

- **index.cshtml**: View principal que renderiza as tabelas de clientes e fornecedores, utilizando o Razor para integrar dados do servidor.

## Requisitos

- [.NET SDK 6.0](https://dotnet.microsoft.com/download/dotnet/6.0) ou superior.
- [Visual Studio](https://visualstudio.microsoft.com/) ou qualquer IDE que suporte ASP.NET Core.

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone <url-do-repositorio>
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd <nome-do-diretorio>
   ```

3. Restaure as dependências:
   ```bash
   dotnet restore
   ```

4. Execute o projeto:
   ```bash
   dotnet run
   ```

5. Acesse a aplicação em seu navegador através do URL `https://localhost:5001` (ou outra porta se especificada).

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request ou um issue para discutir melhorias.

## Licença

Este projeto é licenciado sob a MIT License. Veja o arquivo `LICENSE` para mais detalhes.
