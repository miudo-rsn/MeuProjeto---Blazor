# MeuProjeto - Blazor

Projeto em **Blazor** desenvolvido na disciplina de Desenvolvimento Web (Usabilidade, Dev. Web, Mobile e Jogos) - Anima Educação.

O objetivo é praticar os conceitos básicos do Blazor: roteamento com `@page`, lógica em C# com `@code` e eventos com `@onclick`.

## Tecnologias

- .NET 10
- Blazor Web App
- C# / Razor

## Páginas

| Rota        | Descrição                                                    |
|-------------|--------------------------------------------------------------|
| `/sobre`    | Página "Sobre Mim" com nome completo e descrição do curso    |
| `/contador` | Contador que soma 1 a cada clique no botão                   |
| `/mensagem` | Botão que exibe e oculta uma mensagem de boas-vindas         |
| `/placar`   | Placar com botões de somar, subtrair e zerar (nunca negativo)|

## Estrutura do projeto

```
MeuProjeto---Blazor/
├── Components/        # Páginas, layout e componentes Razor
├── Properties/        # Configurações de execução (launchSettings.json)
├── wwwroot/           # Arquivos estáticos (CSS, imagens)
├── Program.cs         # Ponto de entrada da aplicação
├── MeuProjeto.csproj  # Arquivo do projeto
└── appsettings.json   # Configurações
```

## Como rodar

Pré-requisito: [SDK do .NET 10](https://dotnet.microsoft.com/download) instalado.

```bash
git clone https://github.com/miudo-rsn/MeuProjeto---Blazor.git
cd MeuProjeto---Blazor
dotnet watch
```

O terminal mostra o endereço da aplicação (algo como `http://localhost:XXXX`). Abra no navegador e acrescente a rota da página, por exemplo `/contador`.

Também dá para rodar pelo Visual Studio com **F5**.

## Autor

- [miudo-rsn](https://github.com/miudo-rsn)

## Licença

Distribuído sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
