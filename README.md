# BlazorWasmBrasilApiCep

Atividade de Blazor WebAssembly: consulta de CEP pela BrasilAPI.

- Endpoint: `https://brasilapi.com.br/api/cep/v1/{cep}`
- Digite um CEP de oito dígitos e clique em **Consultar**.
- A aplicação exibe CEP, logradouro, bairro, cidade, estado e serviço retornados pela API.
- Os campos IBGE são exibidos quando retornados. **A API CEP v1 normalmente não fornece esses campos**; nesses casos, a interface informa que não foram disponibilizados.

## Executar

Requer SDK .NET 10.

```bash
dotnet restore
dotnet run
```

Projeto desenvolvido para a disciplina de Usabilidade, Desenvolvimento Web, Mobile e Jogos.
