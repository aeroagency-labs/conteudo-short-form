# Catálogo de Vídeos — Canal YouTube AERO

Atualizado: **2026-09-07** · Canal: **[@aero.agency](https://www.youtube.com/@aero.agency)** · Vídeos catalogados: **33** (vídeos longos do separador *Vídeos*; Shorts não incluídos)

> Fonte de verdade sobre **o que já está publicado** no canal. Não é performance (isso é
> `reports/pulse/`) nem aprendizagem validada (isso é `channel-knowledge.md`) — é o **inventário**
> **do que já foi dito**, para que um guião novo saiba a que se ligar.
>
> Quem lê: `youtube-guiao` (obrigatório, Fase 1.5), e pode ser lido por `youtube-ideias`,
> `youtube-packaging` e `youtube-pulse`.
>
> Serve três decisões, todas em cada guião:
> 1. **Relacionar** — que vídeos já publicados este guião deve referenciar a meio, em fala natural.
> 2. **Indexar** — qual o vídeo passado a linkar no fim (end screen + card).
> 3. **Não repetir** — se o tema já está coberto, dizer ao user antes de escrever (canibalização).
>
> Par deste ficheiro: o **`glossario-metodos.md`** — os nomes próprios criados nos vídeos, para
> serem ditos sempre da mesma maneira.

## Como atualizar

O catálogo tem de refletir **todos** os vídeos do canal. Atualiza sempre que houver publicações
novas — e, no mínimo, quando `youtube-guiao` detetar que está vazio ou com mais de 30 dias.

Ordem de preferência para obter a lista completa:

1. **YouTube Studio → Conteúdo → exportar CSV** (traz título, data, duração, views, retenção).
   O user cola/anexa; a skill preenche as entradas. É a única via que traz **retenção e CTR**.
2. **Página de vídeos do canal** (`https://www.youtube.com/@aero.agency/videos`), quando a sessão
   tiver rede. Dá título, ID, data, duração, views e os capítulos da descrição — foi assim que
   este catálogo foi gerado. (O `WebFetch` bate no consent wall do YouTube; funciona a puxar a
   página com `curl` + cabeçalho `Cookie: SOCS=CAI` e a ler o `ytInitialData`, seguindo os
   tokens de continuação e depois cada `watch?v=` para data/duração/views/descrição.)
3. **O user lista à mão** os vídeos publicados.

Se nenhuma das três estiver disponível, a skill **não inventa catálogo**: escreve o guião na mesma
e regista nas Notas de gravação que a escolha de vídeo a relacionar/indexar ficou por decidir.

Quando um vídeo deste playbook for publicado, **acrescenta-o aqui** no fim do ciclo (passo de
compound do `youtube-guiao`).

### O que está preenchido e o que falta

Preenchido automaticamente a partir do YouTube: título, URL, data, duração, views (à data acima)
e os **capítulos da descrição** (que servem de mapa dos pontos do vídeo). O **pilar é inferido**
do título/capítulos — confirma-o. **Promessa, sistema/metáfora, objeções e o que cada vídeo deixa
em aberto ficam por preencher**: preenche-os à medida que forem sendo usados, ou a partir dos
guiões em `/Users/andrebarbosa/Youtube/scripts/`.

**CTA da descrição, padrão do canal:** newsletter (`ecommercecast.aeroagency.pt`) + auditoria
(`aeroagency.pt/auditoria`), com variantes em `go.aeroagency.pt`. Os vídeos de calculadora apontam
para `metricas.aeroagency.pt`.

## Entradas

Ordenadas do mais recente para o mais antigo.

### Põe as reviews a vender por ti (Shopify)

- **ID:** `poe-as-reviews-a-vender-por-ti-shopify` · **URL:** https://www.youtube.com/watch?v=wjJjAbuFFWA
- **Data:** 2026-09-06 · **Duração:** 12:12 · **Views (2026-09-07):** 5
- **Pilar (inferido — confirmar):** converter
- **Capítulos (pontos do vídeo):**
  - 0:00 Esta loja faz algo que 99% não faz (e um erro caro)
  - 1:17 O erro que sangra dinheiro sem se ver
  - 2:38 O gatilho que falta no carrinho
  - 3:51 O que estão a deixar em cima da mesa
  - 5:50 O que fazem melhor que 99% das lojas
  - 8:31 O pormenor do pós-compra que muda o jogo
- **CTA na descrição:** https://ecommercecast.aeroagency.pt/ · https://aeroagency.pt/auditoria
- **Promessa / sistema / deixa em aberto:** _por preencher_

### O Que Dizer Ao Cliente Depois Do Pagamento | Shopify

- **ID:** `o-que-dizer-ao-cliente-depois-do-pagamento-shopi` · **URL:** https://www.youtube.com/watch?v=wP9AZkOOp1Q
- **Data:** 2026-09-03 · **Duração:** 7:30 · **Views (2026-09-07):** 9
- **Pilar (inferido — confirmar):** reter
- **Capítulos (pontos do vídeo):**
  - 0:00 O que acontece depois de "encomenda confirmada"
  - 1:24 O que a Manuel Alves faz a seguir — e quase ninguém faz
  - 2:47 A página que praticamente todas as lojas desperdiçam
  - 4:31 O detalhe no envio que te está a custar vendas
  - 5:46 Aplica isto hoje
- **CTA na descrição:** https://ecommercecast.aeroagency.pt/ · https://aeroagency.pt/auditoria
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Checkout Shopify: 4 Erros Que Te Custam Vendas

- **ID:** `checkout-shopify-4-erros-que-te-custam-vendas` · **URL:** https://www.youtube.com/watch?v=EtyOcAJ31Hg
- **Data:** 2026-08-30 · **Duração:** 7:51 · **Views (2026-09-07):** 327
- **Pilar (inferido — confirmar):** converter
- **Capítulos (pontos do vídeo):**
  - 0:00 Introdução
  - 1:07 O que já está bem
  - 2:10 Detalhe 1
  - 4:05 Detalhe 2
  - 4:33 Detalhe 3
  - 5:28 Detalhe 4
  - 7:02 Resumo rápido
- **CTA na descrição:** https://go.aeroagency.pt/NGafbCe · https://go.aeroagency.pt/BVGRF9M
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Para de Perder Vendas nas Páginas de Produtos [Shopify]

- **ID:** `para-de-perder-vendas-nas-paginas-de-produtos-sh` · **URL:** https://www.youtube.com/watch?v=rLIPsr8LkyI
- **Data:** 2026-08-26 · **Duração:** 6:10 · **Views (2026-09-07):** 852
- **Pilar (inferido — confirmar):** converter
- **Capítulos (pontos do vídeo):**
  - 0:00 Introdução
  - 0:34 O primeiro elemento que leem
  - 1:29 O teu copy responde a isto?
  - 2:10 Imagens: mostram ou convencem?
  - 3:22 O que a marca faz bem
  - 4:09 O paradoxo mais estranho
  - 5:15 Resumo rápido
  - 5:53 A seguir
- **CTA na descrição:** https://go.aeroagency.pt/o6kj5RE · https://go.aeroagency.pt/wwNuM27
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Ganha Vendas Com Devoluções | Shopify

- **ID:** `ganha-vendas-com-devolucoes-shopify` · **URL:** https://www.youtube.com/watch?v=YV39Vvvd8as
- **Data:** 2026-08-24 · **Duração:** 11:18 · **Views (2026-09-07):** 277
- **Pilar (inferido — confirmar):** reter
- **Capítulos (pontos do vídeo):**
  - 0:00 Introdução
  - 1:24 O problema que ninguém nota
  - 3:04 A loja fala para quem?
  - 4:29 Ouro enterrado
  - 7:41 Uma contradição
  - 8:59 O que falta para converter
  - 10:36 Resumo rápido
  - 11:50 A seguir
- **CTA na descrição:** https://go.aeroagency.pt/nfZ9pT3 · https://go.aeroagency.pt/E9gCMEj
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Cria Anúncios Que Ninguém Pode Copiar [Shopify]

- **ID:** `cria-anuncios-que-ninguem-pode-copiar-shopify` · **URL:** https://www.youtube.com/watch?v=a7lfBZgYk_w
- **Data:** 2026-08-19 · **Duração:** 6:25 · **Views (2026-09-07):** 8 520
- **Pilar (inferido — confirmar):** atrair
- **Capítulos (pontos do vídeo):**
  - 0:00 Introdução
  - 0:39 A primeira pergunta à tua conta
  - 1:44 A segunda pergunta à tua conta
  - 2:29 Um aviso antes de continuar
  - 2:44 O ponto mais crítico
  - 3:27 O que a marca faz bem
  - 4:04 A questão dos descontos
  - 5:31 Resumo rápido
  - 6:12 A seguir
- **CTA na descrição:** https://go.aeroagency.pt/ncFZZKJ · https://go.aeroagency.pt/ozttyMJ
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Baixa o Custo Por Cliente Até 35% na Tua Loja Shopify

- **ID:** `baixa-o-custo-por-cliente-ate-35-na-tua-loja-sho` · **URL:** https://www.youtube.com/watch?v=9vMjtq-UhdI
- **Data:** 2026-08-17 · **Duração:** 5:40 · **Views (2026-09-07):** 12 409
- **Pilar (inferido — confirmar):** atrair
- **Capítulos (pontos do vídeo):**
  - 0:00 Introdução
  - 0:35 Onde começa o problema
  - 1:02 O que isto te está a custar
  - 1:36 A solução
  - 2:49 A métrica que estás a ignorar
  - 3:48 O problema mais português de todos
  - 4:52 Resumo rápido
  - 5:32 A seguir
- **CTA na descrição:** https://go.aeroagency.pt/gop6gww · https://go.aeroagency.pt/7BF6BFL
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Para de Perder os Melhores Clientes na Tua Loja Shopify

- **ID:** `para-de-perder-os-melhores-clientes-na-tua-loja-` · **URL:** https://www.youtube.com/watch?v=op0axYTtGEE
- **Data:** 2026-08-13 · **Duração:** 10:36 · **Views (2026-09-07):** 348
- **Pilar (inferido — confirmar):** reter
- **Capítulos (pontos do vídeo):**
  - 0:00 Introdução
  - 1:08 Três clientes, um erro em comum
  - 2:39 O cliente que ninguém está a ver
  - 4:52 A oportunidade que fica em cima da mesa
  - 6:17 O que se perde no salto para o online
  - 7:18 O silêncio que está a custar caro
  - 8:09 O detalhe que quase todos ignoram
- **CTA na descrição:** https://go.aeroagency.pt/XbxMV5j · https://go.aeroagency.pt/gvhm2eS
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Mais Vendas no Checkout Shopify Sem Mais Tráfego

- **ID:** `mais-vendas-no-checkout-shopify-sem-mais-trafego` · **URL:** https://www.youtube.com/watch?v=smok5fpyI-E
- **Data:** 2026-08-10 · **Duração:** 6:29 · **Views (2026-09-07):** 15 456
- **Pilar (inferido — confirmar):** converter
- **Capítulos (pontos do vídeo):**
  - 0:00  A compra não acaba onde pensas
  - 0:36  Erro #1 — logo à entrada
  - 1:37  Erro #2 — o caminho até pagar
  - 2:30  Erro #3 — a conta que não bate certo
  - 3:14  Erro #4 — a pergunta que fica no ar
  - 4:02  Erro #5 — quem fica de fora
  - 5:03  Erro #6 — o último obstáculo
  - 5:39  Como corrigir os 6
- **CTA na descrição:** https://go.aeroagency.pt/EfigYzm · https://go.aeroagency.pt/KH8NZzR
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Faz o Cliente Voltar à Tua Loja Shopify (Custo Zero)

- **ID:** `faz-o-cliente-voltar-tua-loja-shopify-custo-zero` · **URL:** https://www.youtube.com/watch?v=FwIG7QpItZE
- **Data:** 2026-08-09 · **Duração:** 7:24 · **Views (2026-09-07):** 1 112
- **Pilar (inferido — confirmar):** reter
- **Capítulos (pontos do vídeo):**
  - 0:00  A venda não termina no "comprar"
  - 0:51  Falha #1 — o momento logo a seguir ao pagamento
  - 2:23  Falha #2 — o que devias enviar (e não envias)
  - 3:42  Falha #3 — o que chega à porta do cliente
  - 4:55  Falha #4 — o que nunca chegas a perguntar
  - 6:23  Como corrigir as 4
- **CTA na descrição:** https://go.aeroagency.pt/XKH5s25 · https://go.aeroagency.pt/ybT3wHo
- **Promessa / sistema / deixa em aberto:** _por preencher_

### O Teu Site Está A Mentir-Te Sobre As Vendas

- **ID:** `o-teu-site-esta-a-mentir-te-sobre-as-vendas` · **URL:** https://www.youtube.com/watch?v=U_vl3-l294o
- **Data:** 2026-06-24 · **Duração:** 4:51 · **Views (2026-09-07):** 38 151
- **Pilar (inferido — confirmar):** converter
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://go.aeroagency.pt/3zCGCGD · https://go.aeroagency.pt/z5QVGRM
- **Promessa / sistema / deixa em aberto:** _por preencher_

### O Erro que Faz a Tua Loja Não Vender

- **ID:** `o-erro-que-faz-a-tua-loja-nao-vender` · **URL:** https://www.youtube.com/watch?v=tokFRZWuj_I
- **Data:** 2026-06-24 · **Duração:** 7:27 · **Views (2026-09-07):** 6 292
- **Pilar (inferido — confirmar):** converter
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://go.aeroagency.pt/QyKoFsT · https://go.aeroagency.pt/WaW9fAS
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Copia Esta Estratégia de Anúncios de Branding

- **ID:** `copia-esta-estrategia-de-anuncios-de-branding` · **URL:** https://www.youtube.com/watch?v=Xjokuv0mv_k
- **Data:** 2026-05-21 · **Duração:** 6:08 · **Views (2026-09-07):** 23 854
- **Pilar (inferido — confirmar):** atrair
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://go.aeroagency.pt/kRRTJTb · https://go.aeroagency.pt/KsXvp4P
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Copia Este Modelo de Fidelização Para o Teu Negócio

- **ID:** `copia-este-modelo-de-fidelizacao-para-o-teu-nego` · **URL:** https://www.youtube.com/watch?v=K7pY3ONlQmw
- **Data:** 2026-05-18 · **Duração:** 3:42 · **Views (2026-09-07):** 29 831
- **Pilar (inferido — confirmar):** reter
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://go.aeroagency.pt/mTzJbPZ · https://go.aeroagency.pt/ygrzTa8
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Vais PERDER Clientes, Se Não Fizeres Isto

- **ID:** `vais-perder-clientes-se-nao-fizeres-isto` · **URL:** https://www.youtube.com/watch?v=5gYT3LTjzbw
- **Data:** 2026-05-09 · **Duração:** 6:35 · **Views (2026-09-07):** 14 222
- **Pilar (inferido — confirmar):** reter
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://go.aeroagency.pt/d8baN9n · https://go.aeroagency.pt/J4Ps2sX
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Muda Isto e PARA de Perder Vendas

- **ID:** `muda-isto-e-para-de-perder-vendas` · **URL:** https://www.youtube.com/watch?v=T6FwTfA9cWQ
- **Data:** 2026-05-08 · **Duração:** 7:14 · **Views (2026-09-07):** 7 668
- **Pilar (inferido — confirmar):** converter
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://go.aeroagency.pt/aBHjZdo · https://go.aeroagency.pt/9kDgxLB
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Os clientes NÃO compram, até fazeres isto

- **ID:** `os-clientes-nao-compram-ate-fazeres-isto` · **URL:** https://www.youtube.com/watch?v=1XLn6GjeDns
- **Data:** 2026-04-08 · **Duração:** 4:38 · **Views (2026-09-07):** 23 353
- **Pilar (inferido — confirmar):** converter
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://go.aeroagency.pt/XijmWxH · https://go.aeroagency.pt/r8ADCuV
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Copia esta estratégia de anúncios, vai EXPLODIR o teu negócio

- **ID:** `copia-esta-estrategia-de-anuncios-vai-explodir-o` · **URL:** https://www.youtube.com/watch?v=se-h8_o5nCg
- **Data:** 2026-04-03 · **Duração:** 4:07 · **Views (2026-09-07):** 1 691
- **Pilar (inferido — confirmar):** atrair
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://go.aeroagency.pt/KSboVRK · https://go.aeroagency.pt/GYtET3P
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Copia esta estratégia de retenção, vai EXPLODIR o teu negócio

- **ID:** `copia-esta-estrategia-de-retencao-vai-explodir-o` · **URL:** https://www.youtube.com/watch?v=1zltVpRMG7s
- **Data:** 2026-04-03 · **Duração:** 4:35 · **Views (2026-09-07):** 23 788
- **Pilar (inferido — confirmar):** reter
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://go.aeroagency.pt/GpyXQFT · https://go.aeroagency.pt/Vy6x6VL
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Copia esta estratégia, vais vender MAIS aos MESMOS clientes

- **ID:** `copia-esta-estrategia-vais-vender-mais-aos-mesmo` · **URL:** https://www.youtube.com/watch?v=svpmFSQgkCY
- **Data:** 2026-03-27 · **Duração:** 4:44 · **Views (2026-09-07):** 4 689
- **Pilar (inferido — confirmar):** reter
- **Capítulos (pontos do vídeo):**
  - 0:00 Onde tudo para depois da compra
  - 0:14 O nosso sistema de recompra
  - 1:00 Problema #1
  - 2:55 Problema #2
  - 3:26 Problema #3
  - 4:03 O que podes melhorar
- **CTA na descrição:** https://go.aeroagency.pt/smawSSf · https://go.aeroagency.pt/Hj8V2ab
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Estás a PERDER dinheiro, se ainda fazes isto

- **ID:** `estas-a-perder-dinheiro-se-ainda-fazes-isto` · **URL:** https://www.youtube.com/watch?v=7nS20hmbJrE
- **Data:** 2026-03-26 · **Duração:** 4:47 · **Views (2026-09-07):** 5 449
- **Pilar (inferido — confirmar):** converter
- **Capítulos (pontos do vídeo):**
  - 0:00 A página de produto é decisiva
  - 0:30 Como já ajudamos mais de 50 lojas
  - 1:04 Problema #1
  - 1:54 Problema #2
  - 2:47 Problema #3
  - 3:26 Problema #4
  - 4:02 O que podes mudar
- **CTA na descrição:** https://go.aeroagency.pt/yKiYdvr · https://go.aeroagency.pt/M6EAHd7
- **Promessa / sistema / deixa em aberto:** _por preencher_

### O Check-Out que 28 Lojas Utilizam para Vender MAIS

- **ID:** `o-check-out-que-28-lojas-utilizam-para-vender-ma` · **URL:** https://www.youtube.com/watch?v=8LTqLzEchb8
- **Data:** 2026-03-20 · **Duração:** 5:14 · **Views (2026-09-07):** 6 719
- **Pilar (inferido — confirmar):** converter
- **Capítulos (pontos do vídeo):**
  - 0:00 70% dos clientes não compram
  - 0:41 O que podes aprender com o gato preto
  - 0:56 Problema #1
  - 1:43 Problema #2
  - 2:42 Problema #3
  - 3:23 Problema #4
  - 4:00 Problema #5
  - 4:38 O que mudar na tua loja
- **CTA na descrição:** https://go.aeroagency.pt/vCAXmaT · https://go.aeroagency.pt/JX5LbxC
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Auditoria de Loja Shopify: Porque razão a tua estratégia de Google Ads está a falhar?

- **ID:** `auditoria-de-loja-shopify-porque-razao-a-tua-est` · **URL:** https://www.youtube.com/watch?v=xKuEzi42YA4
- **Data:** 2026-02-23 · **Duração:** 9:52 · **Views (2026-09-07):** 1 286
- **Pilar (inferido — confirmar):** atrair
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://go.aeroagency.pt/DnxxmEF · https://go.aeroagency.pt/QaiW7BD
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Bloqueios de Conversão Invisíveis na Tua Loja Online

- **ID:** `bloqueios-de-conversao-invisiveis-na-tua-loja-on` · **URL:** https://www.youtube.com/watch?v=cXW1uHq1t-c
- **Data:** 2025-12-29 · **Duração:** 21:10 · **Views (2026-09-07):** 9 606
- **Pilar (inferido — confirmar):** converter
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://go.aeroagency.pt/Cn7pcus · https://go.aeroagency.pt/R5TxtWB
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Não Invistas em Google Ads Antes de Ver Isto | Para Lojas Online

- **ID:** `nao-invistas-em-google-ads-antes-de-ver-isto-par` · **URL:** https://www.youtube.com/watch?v=NFxqnSwV91A
- **Data:** 2025-12-11 · **Duração:** 6:53 · **Views (2026-09-07):** 13 121
- **Pilar (inferido — confirmar):** atrair
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://go.aeroagency.pt/k8HXbm8 · https://go.aeroagency.pt/yH69Qv4 · https://bio.aeroagency.pt/
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Tens uma loja online, estás a perder margem ao tentar vender produtos de baixo ticket

- **ID:** `tens-uma-loja-online-estas-a-perder-margem-ao-te` · **URL:** https://www.youtube.com/watch?v=_p0E2piwac8
- **Data:** 2025-11-28 · **Duração:** 7:40 · **Views (2026-09-07):** 11 070
- **Pilar (inferido — confirmar):** converter
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://go.aeroagency.pt/hzsSSvy · https://go.aeroagency.pt/cjCY66i
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Se tens uma loja online, os teus métodos de pagamento estão a matar as vendas 💳

- **ID:** `se-tens-uma-loja-online-os-teus-metodos-de-pagam` · **URL:** https://www.youtube.com/watch?v=M0U9fog7qaU
- **Data:** 2025-11-11 · **Duração:** 9:59 · **Views (2026-09-07):** 17 002
- **Pilar (inferido — confirmar):** converter
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://go.aeroagency.pt/mmNcLnS · https://go.aeroagency.pt/JvkWB25
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Aumenta a Recompra e o LTV na Tua Loja Online

- **ID:** `aumenta-a-recompra-e-o-ltv-na-tua-loja-online` · **URL:** https://www.youtube.com/watch?v=lYABGIhbtmw
- **Data:** 2025-11-05 · **Duração:** 9:00 · **Views (2026-09-07):** 42 090
- **Pilar (inferido — confirmar):** reter
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://go.aeroagency.pt/59TchRw · https://go.aeroagency.pt/VvrYryo
- **Promessa / sistema / deixa em aberto:** _por preencher_

### A Publicidade Online Dá Resultado? (Calcula Agora) [Calculadora 2]

- **ID:** `a-publicidade-online-da-resultado-calcula-agora-` · **URL:** https://www.youtube.com/watch?v=o88GX2MWL4A
- **Data:** 2025-10-28 · **Duração:** 8:45 · **Views (2026-09-07):** 16 083
- **Pilar (inferido — confirmar):** atrair
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://metricas.aeroagency.pt/ · https://go.aeroagency.pt/Sq6gBqD · https://go.aeroagency.pt/dmjsQdS
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Precisas Destes Números para Planear Campanhas! [Calculadora 3]

- **ID:** `precisas-destes-numeros-para-planear-campanhas-c` · **URL:** https://www.youtube.com/watch?v=I-dqSqFJyJc
- **Data:** 2025-10-28 · **Duração:** 12:47 · **Views (2026-09-07):** 9 400
- **Pilar (inferido — confirmar):** atrair
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://metricas.aeroagency.pt/ · https://go.aeroagency.pt/Guymdhr · https://go.aeroagency.pt/kzKirqx
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Calcula as Tuas Margens! (Garante que tens LUCRO todos os meses) [Calculadora 1]

- **ID:** `calcula-as-tuas-margens-garante-que-tens-lucro-t` · **URL:** https://www.youtube.com/watch?v=SLNNm7bC_7w
- **Data:** 2025-10-20 · **Duração:** 9:27 · **Views (2026-09-07):** 12 123
- **Pilar (inferido — confirmar):** transversal (margem/lucro)
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://metricas.aeroagency.pt/ · https://go.aeroagency.pt/uFjAGrr · https://go.aeroagency.pt/WsDRxWb
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Como Calcular Margem de Desconto? (Sem Perder LUCRO) [Calculadora 5]

- **ID:** `como-calcular-margem-de-desconto-sem-perder-lucr` · **URL:** https://www.youtube.com/watch?v=V5YlPFX7TwY
- **Data:** 2025-10-15 · **Duração:** 8:40 · **Views (2026-09-07):** 30 069
- **Pilar (inferido — confirmar):** transversal (margem/lucro)
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://metricas.aeroagency.pt/ · https://go.aeroagency.pt/jGo7Shx · https://go.aeroagency.pt/WW5bUrg
- **Promessa / sistema / deixa em aberto:** _por preencher_

### Prepara a Melhor Black Friday de Sempre [2025]

- **ID:** `prepara-a-melhor-black-friday-de-sempre-2025` · **URL:** https://www.youtube.com/watch?v=KbsrWwm0Qxo
- **Data:** 2025-09-26 · **Duração:** 79:47 · **Views (2026-09-07):** 21 687
- **Pilar (inferido — confirmar):** transversal (sazonal/Q4)
- **Capítulos:** sem capítulos na descrição
- **CTA na descrição:** https://go.aeroagency.pt/mZVGMfb · https://go.aeroagency.pt/UVZrDZt · https://masterclass.aeroagency.pt · https://margem.aerotools.pt/
- **Promessa / sistema / deixa em aberto:** _por preencher_

## Mapa por pilar

| Pilar | Vídeos publicados |
|---|---|
| Atrair | 8 |
| Converter | 13 |
| Reter | 9 |
| Transversal (margem/lucro) | 2 |
| Transversal (sazonal/Q4) | 1 |

Leitura rápida (a confirmar com dados de retenção): o canal está **pesado em converter e reter**,
com uma linha forte de teardowns de checkout/página de produto em Shopify e uma linha de
calculadoras de margem. **Atrair** vive sobretudo em Google Ads e criativos.

