## Ferramentas MCP

| Tool | O que faz |
|---|---|
| `comecar` | Fase 0: boas-vindas e consentimento |
| `registar` | Guarda nome, email, loja (só com `consentimento: true`) e devolve `sessao_id` + fase 1 |
| `proxima_fase` | Devolve as instruções da fase seguinte (1 → 8) |
| `concorrencia_preparar` | Janelas da época alta passada + links Meta Ads Library / Google Ads Transparency por concorrente |
| `concorrencia_registar` | Recebe os anúncios lidos, filtra (só os que arrancaram na janela e já terminaram), agrupa em campanhas, lê sinais (longevidade ≥ 30 dias, ≥ 3 variações, arranque antes da BF, oferta acima do máximo da loja) e devolve `concorrencia_id` |
| `gerar_plano` | Calcula o plano, guarda-o e devolve o link `/plano/<id>` |
| `comparar_ofertas` | Compara por encomenda: desconto em %, leve 3 pague 2, pack, progressivo, brinde, vale e portes grátis (quanto sobra, encomendas para empatar, mínimo por 1€ em anúncios) |
| `simular_desconto` | Regra do Empate para um produto e um desconto |

