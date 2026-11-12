# Repurpose — de 1 vídeo para muitos ativos (e-commerce, Ed Lawrence)

> Princípio do Ed: **um vídeo de YouTube é a peça-mãe.** Dele saem LinkedIn, shorts/reels,
> emails, tweets, carrosséis. *"You can build one video into LinkedIn posts, shorts, clips,
> reels, tweets, emails."* O YouTube aquece; o email/comunidade vende.
> Avatar: donos de loja €100k+. Oferta: serviço de performance marketing.

## Princípios transversais
- **A história/insight viaja, o formato muda.** Mantém o ângulo, adapta o ritmo a cada plataforma.
- **Emails que performam dão os melhores vídeos** (e vice-versa) — testa o ângulo no canal de menor risco.
- **CTA por resultado**, nunca "vê o meu vídeo/compra a minha cena". Vende o benefício.
- **PT-PT, "tu", tom direto sem hype.** Casos anonimizados.

---

## 1. TEASER (para WhatsApp / comunidade / descrição)
Gera curiosidade sem revelar a resposta.
```
🎬 Vídeo novo:

→ [gancho principal — provocador]
→ [dado/insight surpreendente]
→ [ação prática ou resultado]
→ [opcional]

Vê até ao fim 👆 [link]
```
Regras: 3-5 bullets (1 linha cada), "→" como bullet, emojis só no cabeçalho/fecho, não dar a resposta.

## 2. EMAIL (a peça que VENDE — sistema do Ed)
O email leva o subscritor a ver o vídeo OU direto para a oferta.
- **Estrutura (6 passos):** ideia (= ângulo do vídeo) → headline (testa um possível título) → corpo no padrão *"aconteceu-me isto (bom/mau) → o que aprendi → como tu tens o mesmo resultado"* → editar (cortar gordura) → CTA → enviar.
- Curto, "toilet-readable". Uma ideia, uma ação.
- **CTA cedo** (não só no fim) e por resultado.
- Variante de venda: dar valor durante a semana, depois UM email com a oferta (call/aplicação).

## 3. SHORTS / REELS / CLIPS
- Tirar do vídeo os momentos de maior tensão: o **hook**, uma **história** completa curta, ou um **passo** auto-contido.
- Cada clip precisa do SEU mini-hook nos primeiros 1-2s (não começa a meio).
- Texto no ecrã; legível sem som ("designed to be listened to OR read").
- Um clip = uma ideia/lição. CTA suave: "vídeo completo no canal".

## 4. LINKEDIN
- O insight do vídeo vira post. Reaproveitar o sistema que já existe na skill `linkedin-post-generator` (estilos PAIPS, Contrarian, Listicle, etc.).
- Hook do post pode reusar o hook do vídeo.
- Para gerar de facto o post, encaminhar para `linkedin-post-generator` (não duplicar aqui).

## 5. TWEET / THREAD (opcional)
- A lição central em 1 tweet (mnemónica/contrarian) + thread com os passos.
- Treino de baixo risco para o ângulo do próximo vídeo.

---

## O que esta skill produz (escolhe conforme o pedido)
Por defeito, do guião/tema dado, gerar o **pacote de repurpose**:
1. **Teaser** (WhatsApp/comunidade).
2. **Email** (1, no sistema do Ed).
3. **3-5 ideias de clip/short** (com timestamp/momento + mini-hook de cada).
4. **1-2 ganchos de LinkedIn** (e encaminhar para `linkedin-post-generator` para o post final).
Se o user pedir só uma peça (ex: "só o email"), gerar só essa.
