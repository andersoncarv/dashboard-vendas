<!--

# dashboard_vendas

Breve descrição de 1-2 frases: o que este relatório/modelo mede e para quem.

## Modelo de dados

<!--
Descreva o esquema em alto nível. No seu caso, por exemplo:
- `Vendas` (grão: 1 linha por venda) com colunas Produto e Valor.
- `Medidas` — tabela dedicada só de medidas DAX (Total de Vendas, Ticket Médio),
  separada da tabela de dados por decisão tomada no Módulo 3.
-->

## Dicionário de dados (básico)

| Tabela | Coluna/Medida | Tipo | Descrição |
|--------|---------------|------|-----------|
| Vendas | Produto | Texto | Nome do produto vendido |
| Vendas | Valor | Inteiro | Valor da venda |
| Medidas | Total de Vendas | Medida DAX | Soma de vendas com valor ≥ 100, arredondada |
| Medidas | Ticket Médio | Medida DAX | Média do valor por venda |

## Frequência de atualização

<!-- Ex.: "dados de exemplo, sem atualização automática" -->

## Como contribuir

1. Clone o repositório e abra `dashboard_vendas.pbip` no Power BI Desktop (PBIP + TMDL habilitados em Opções > Versão Prévia).
2. Crie uma branch: `git checkout -b feature/<sua-alteracao>`.
3. Altere o modelo, salve, revise o diff no VS Code.
4. Commit seguindo Conventional Commits (`feat:`, `fix:`, `docs:`...).
5. `git push origin feature/<sua-alteracao>` e abra um Pull Request.

-->: