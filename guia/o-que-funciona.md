# O que funciona nos nossos scripts (e o que falhou em novembro)

Análise dos 48 scripts da app Script Spot exportados a 12 nov 2026 ([fontes/scripts-app](../fontes/scripts-app/)). Referência de qualidade: **agosto** (e abril para os temas básicos). Novembro foi considerado mais fraco em reunião; os números abaixo mostram porquê.

## Os números

| Mês | Scripts | Palavras por script | Palavras por linha | Hooks por script | Abre com história | Acaba em "faz isto hoje" | "Ou seja" | Assinatura de marca |
|---|---|---|---|---|---|---|---|---|
| Abril | 18 | 113 | 5,7 | 4,7 | 3 | 0 | 3 | 0 |
| Agosto | 19 | 197 | 6,0 | 8,4 | 12 | 0 | 1 | 9 |
| Novembro | 10 | 162 | **10,7** | 6,3 | **0** | **8** | **7** | 0 |

"Abre com história": começa numa situação concreta ("Tínhamos um cliente…", "Esta loja online…", "Hoje tive quatro reuniões", "Contratámos o Claude…"). "Assinatura de marca": fecha com "uma loja online não se gere só nos anúncios… é aí que está a diferença" ou equivalente.

## O que agosto faz bem

1. **Abre numa cena, não numa ideia.** "Esta loja online podia ter comprado um Porsche 911." "Dois clientes entram na tua loja online." "Deixa-me contar-te o pior dia desta loja online." O espectador vê alguma coisa antes de ouvir a tese.
2. **Frases curtíssimas, uma por linha.** Seis palavras por linha em média. Lê-se ao ritmo da fala e corta-se bem na edição.
3. **Reticências como pausa dramática.** Todas as 19 usam "…" para segurar a frase antes da revelação: "E então… esgotou."
4. **Uma escalada clara em 4-5 blocos.** Situação concreta → agravamento ("E aqui está o que ninguém te conta") → nome da solução ("Chama-se BigQuery.") → resultado → moral.
5. **Um número ou objeto memorável.** Porsche 911, Ferrari, meio milhão parado, 20 mil produtos com ROAS 1,90, 2 mil euros vs 20 euros, mais 162% de compras registadas.
6. **Palavras em maiúsculas só onde a voz sobe.** PORSCHE, FERRARI, ESQUECEU, BIG QUERY. Pouco e de propósito.
7. **Muitos hooks, todos diferentes no ângulo.** 8 a 12 variações: número, confissão, contrário, pergunta direta, prova. Prontos para testar.
8. **Fecho com posicionamento.** "Uma loja online não se gere só nos anúncios. Gere-se no negócio todo. E é aí que está a diferença." Liga cada dica à tese da Aero.
9. **CTA curto e concreto.** "Queres saber onde está o teu Ferrari escondido? Clica aqui."

## O que abril faz bem (temas básicos)

- Explica o conceito em linguagem de dono de loja, sem jargão: "é uma forma de garantir que a tua loja não perde essa informação".
- Estrutura simples problema → solução → "Resultado?" com três bullets falados.
- Bom modelo para os vídeos "mais básicos" de Server-Side e BigQuery pedidos agora.
- Fraqueza: hooks genéricos ("Tens uma loja online?…") e quase sem CTA.

## Onde novembro falhou

1. **Frases longas.** Quase 11 palavras por linha. Soa a texto lido, não a conversa. Ex.: "Pelo que temos visto, quem tem provas: avaliações, respostas às dúvidas, informação clara."
2. **Nenhuma abertura com cena.** Começam todos pela tese ou por uma instrução ("Pega no telemóvel e abre o ChatGPT").
3. **Viraram tutoriais.** 8 em 10 acabam em "Faz isto hoje: abre X, vai a Y, carrega em Z". Caminhos de menu ("Relatórios, Aquisição, Aquisição de tráfego") não funcionam em 40 segundos falados; servem para um vídeo longo ou para o ecrã.
4. **Hesitação.** "Pelo que temos visto", "honestamente", "se calhar". Tira autoridade.
5. **"Ou seja" como muleta.** Aparece em 7 de 10. Sinal de que a ideia não ficou clara à primeira.
6. **Sem pausas nem ritmo.** Zero reticências. O texto não marca onde a voz respira.
7. **CTA longo e repetido.** "Se quiseres saber X, candidata-te à auditoria no link. Só fazemos duas ou três por mês." igual em quase todos.
8. **Variações demasiado parecidas com o original.** As "Variação |" mudam o enquadramento mas não a cena nem o objeto memorável.

## Regras práticas que saem daqui

- Primeira linha do corpo = uma cena com um sujeito concreto (uma loja, um cliente, um dia, uma reunião).
- No máximo 8 palavras por linha. Uma ideia por linha.
- 4 a 6 blocos marcados com `[↺]`. Cada bloco avança a história; se não avança, corta.
- Um número ou objeto memorável por script.
- O "como fazer" passo a passo fica para o vídeo longo. No short entra só o primeiro passo, numa frase.
- Sem "pelo que temos visto", "honestamente", "se calhar", "ou seja".
- Fecho com a tese da Aero, variando a formulação.
- CTA numa linha, com o objeto do vídeo: "Queres saber onde está o teu Ferrari escondido? Clica aqui."
- 6 a 10 hooks por script, cada um com um ângulo diferente.
- Palavras em maiúsculas só em 1 a 3 sítios onde a voz sobe.

Estas regras complementam os frameworks em [../frameworks/](../frameworks/).
