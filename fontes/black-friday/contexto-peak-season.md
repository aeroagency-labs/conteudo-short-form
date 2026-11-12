# Contexto extraído do aero-playbook — Peak Season

Fonte: `aeroagency-labs/aero-playbook` › `commands/campanha-peak-season.md`, `commands/peak-season-executar.md`, `references/epoca-alta.md`.

## Datas 2026
- Black Friday: sexta 27 nov (sexta a seguir à 4.ª quinta de novembro, 26 nov)
- BF + Cyber Monday = campanha única de 4 dias: 27–30 nov
- Pré-BF, 4 blocos de sexta a quinta: 30 out–5 nov · 6–12 nov · 13–19 nov · 20–26 nov
- Pós-Natal / Campanha de Reis: 26 dez – 6 jan

## Princípios do método
1. Outubro também tem de vender (além de captar lista).
2. A concorrência investe mais: CPMs sobem, lista própria aquecida vale mais.
3. Não reinventar a roda: partir do que já resultou em anos anteriores.
4. Anúncios: nunca campanhas de 1-2 dias. Piso 4 dias, preferência 7. Janelas curtas só na lista (email/SMS/WhatsApp).
5. A pesquisa por "Natal" começa em meados de outubro.
6. Objetivo fixo da época: maximizar volume de vendas.

## Fases
| Fase | Janela |
|---|---|
| Captação de lista | Outubro, a par da venda normal |
| Pré-BF / aquecimento | 4 blocos de 7 dias (sexta a quinta), escalada por categoria |
| BF + Cyber Monday | 4 dias, sexta a segunda |
| Pré-Natal | início/meados dez até ao prazo-limite de entrega |
| Natal / última entrega | até à(s) data(s)-limite (pode haver vários níveis: personalizados vs stock) |
| Campanha de Reis (opcional) | 26 dez – 6 jan |

Modos de Natal: com desconto · sem desconto (curadoria/gift guide + urgência de entrega) · não aplica.

Estrutura da BF: desconto decrescente anunciado (urgência) ou extensão (risco de prática enganosa em PT/UE se se anuncia um fim falso).

## Três pistas
- **Não lista** (sempre): Meta + Google Ads direto à oferta.
- **Lista** (se base relevante): recebe primeiro ou condições melhores; não paga CPM.
- **Afiliados** (se programa ativo): risco de fuga do cupão para sites agregadores.

Funis de captação em outubro: lead ads → LP → email → SMS/WhatsApp; lead ads diretos → email; pop-up → email.

## Cadência de email
| Fase | Cadência |
|---|---|
| Outubro (contexto) | 1/semana |
| Pré-BF | 1-2/semana |
| Semana BF | quase diário |
| Cyber Monday | 1 dedicado |
| Pré-Natal | 2-3/semana |
| Últimos dias antes do prazo | 1-2/dia |
| Reis | 1-2 |

Arco por segmento: cliente = aquecimento → campanha; lead = contexto → aquecimento → campanha.

## Biblioteca de táticas (com pré-condição)
- Escalada de desconto pré-BF por categoria (nenhuma)
- Aquecimento criativo / demanda reprimida (capacidade criativa)
- Acesso antecipado por lista (lista relevante)
- Flash sale (só na lista)
- Vale em vez de devolução (nenhuma)
- **Garantia de diferença de preço** (sempre proposta): "compra agora, se ficar mais barato na BF devolvemos a diferença"
- Pontos em dobro resgatáveis jan-mar (sistema de pontos)
- Subir threshold de BNPL na época (Klarna/Sequra/Cofidis)
- Produto-isca / hero products
- Bundles/kits (marca própria)
- Comunicação de escassez (stock limitado)
- Lançamentos dentro/fora do desconto (decisão obrigatória)
- Mystery box (categorias de descoberta)
- Semana final acumula todas as categorias
- Não chamar "Black Friday" (marcas premium)
- Loja física vs online

## Regra de acumulação de descontos (obrigatória)
Para always-on × newsletter × afiliado × pontos × oferta da época: não acumula / acumula com teto / acumula sem teto (com desconto efetivo calculado).

## Inputs de análise
- Época passada (o que se fez, resultado, aprendizagens)
- Best sellers da época alta vs período normal (para sequenciar categorias por semana)
- Concorrência na Meta Ads Library — janela da época alta do ano anterior, nunca o presente
- NotebookLM do cliente como gerador de ideias; o método decide (aceite/adaptada/rejeitada)
- Racional de cada campanha com fonte concreta

## Workflow do comando (resumo)
0 pré-voo NotebookLM → 1-5 ler contexto, homólogo e vendas por produto mês a mês → 6 Gate 0 confirmar época passada → 7 perguntas bloqueantes (Natal, mercados, concorrentes, desconto máximo, lista, prazos) → 8-9 concorrência → 10-12 NotebookLM + filtragem → 13-16 esqueleto, pistas, emails, acumulação → 17 racional → 18 comparação → 19 Gate 1 → 20 guardar plano → 21 apresentação cliente-ready.
Depois da reunião: `/peak-season-executar` cria campanhas, pedidos de design e tarefas.
