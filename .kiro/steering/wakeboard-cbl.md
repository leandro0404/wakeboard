# Wakeboard CBL — Guia de Conteúdo do Site

Este arquivo define o conteúdo, estrutura e tom do site de wakeboard para iniciantes no CBL.
Use como referência ao gerar ou atualizar qualquer página do site.

---

## Contexto

- Pista: **CBL** (circuito fechado, sentido **horário**)
- Público-alvo: **iniciantes** que estão aprendendo wakeboard do zero
- Tom: direto, prático, sem frescura — como um amigo que já roda te explicando
- Bases cobertas: **Regular** (pé esquerdo na frente) e **Goofy** (pé direito na frente)

---

## Estrutura do Site

### 1. Equipamento para começar
- Prancha (tamanho por peso/altura)
- Colete obrigatório
- Rope e handle
- Capacete (recomendado no início)
- Roupa de proteção / lycra

### 2. Primeiros passos fora da água
- Posição dos pés na prancha (stance)
- Regular vs Goofy — como descobrir o seu
- Como segurar o handle
- Posição do corpo no dock start

### 3. Dock start — saindo da beira
- Agachar com joelhos dobrados
- Deixar o cabo puxar, não forçar
- Olhar pra frente, não pra baixo
- Primeiros metros: prancha plana na água

### 4. Primeiras voltas — só rodar
- Manter o cabo tenso
- Absorver as curvas com os joelhos
- Não resistir nas polias, deixar o cabo trabalhar
- Dica: olhar sempre para o próximo ponto da pista

### 5. Mapa da pista CBL
Seção visual com o mapa desenhado + legenda de cada obstáculo.
O mapa está em `wake_cbl_mapa_ paint.png` na raiz do projeto.

**Obstáculos e dicas:**

| Obstáculo | Descrição | Nível |
|-----------|-----------|-------|
| **Dock Start** | Ponto de entrada na pista | — |
| **Incliner** | Rampa lateral esquerda, boa para ganhar confiança em subir | Iniciante |
| **Flat Bar** (x2) | Slide reto — agachar antes de subir, manter o peso centralizado | Iniciante |
| **Kicker** (x2) | Rampa de salto — começar pelo menor, olhar pra frente no ar | Iniciante/Médio |
| **Transfer** | Obstáculo atravessado, exige timing na abordagem | Médio |
| **Fibonat** | Corrimão curvo, bom para BS slides | Médio |
| **Rooftop** | Telhado — obstáculo de nível intermediário/avançado | Avançado |
| **Jump/Olie** | Obstáculo na torre da ponta direita — sem rampa, serve para dar olie ou salto simples passando por cima | Iniciante/Médio |

### 6. Dicas por base — curvas e técnica

**Como fazer as curvas no CBL (sentido horário):**

| Base | Curva | O que fazer |
|------|-------|-------------|
| **Regular** | Abre (esquerda) | Calcanhar — heelside |
| **Regular** | Fecha (direita) | Ponta dos pés — toeside |
| **Goofy** | Abre (direita) | Ponta dos pés — toeside |
| **Goofy** | Fecha (esquerda) | Calcanhar — heelside |

**Dicas de cavada por situação:**

- **Curvas normais da pista:** cavada suave, joelhos dobrados absorvendo — não força, deixa o cabo trabalhar
- **Antes de obstáculo:** solta a cavada uns 2 metros antes, entra neutro em cima do obstáculo
- **Incliner:** praticamente não cava — só direciona a prancha pra cima da rampa, o cabo já puxa você por cima
- **Kicker:** pequena cavada heelside antes pra ganhar velocidade, depois neutro na subida
- **Flat bar:** cavada progressiva bem leve, partindo sempre de baixo do cabo para ir ao obstáculo — entra neutro em cima, sem cavar. Usar a posição debaixo do cabo como referência fixa garante sempre a mesma abordagem

**Regular (pé esquerdo na frente):**
- No sentido horário do CBL, as curvas fechadas ficam no lado do heel
- O lado esquerdo da pista favorece abordagem mais natural nos obstáculos
- Kicker do topo: abordagem heelside — peso no calcanhar na saída

**Goofy (pé direito na frente):**
- No sentido horário, as abordagens ficam mais em toeside
- O kicker do topo fica em abordagem toeside — manter o peso centralizado
- Flat bars ficam em abordagem backside — ombro da frente aponta pro obstáculo

### 7. Macetes gerais da pista
- Nunca solte o handle dentro da pista (risco de se machucar com o cabo)
- Caia de lado, nunca de frente
- Se vai cair, solta o handle e caia longe do obstáculo
- Espere o cabo afundar antes de nadar de volta ao deck
- Regra da pista: quem caiu fica na lateral, não no meio do percurso
- Ao passar na frente do dock start e ver alguém saindo: vá para a rampa (incliner) e evite a flat bar — o tranco de quem inicia pode folgar o cabo ou variar a velocidade e desestabilizar em cima do obstáculo
- Na dúvida sobre um obstáculo: primeira vez sem trick, só passar por cima

---

## Referências visuais

- Mapa da pista: `wake_cbl_mapa_ paint.png` (desenho feito no Paint, visão de cima)
- Sentido da pista: horário, com **5 torres** (polias)
- A torre da ponta direita tem um obstáculo simples (tipo jump/olie) — sem nome definido ainda
- Imagens externas a buscar: dock start, flat bar slide, kicker, posição de queda segura

---

## Canais e links recomendados

Seção do site com referências externas para quem quer aprender mais.

| Canal | URL | Destaque |
|-------|-----|----------|
| **CBL** | [Playlist iniciante](https://www.youtube.com/watch?v=15KZ-swzWE8&list=PLI5Vcra_PrsWc5NLL2FpJEGcDaA4E3cNR) | Playlist oficial do CBL para quem está começando 🇧🇷 |
| **Julia Rick** | [youtube.com/@JuliaRick](https://www.youtube.com/@JuliaRick) | Wakeboarder brasileira |
| **The Peacock Brothers** | [youtube.com/@ThePeacockBrothers](https://www.youtube.com/@ThePeacockBrothers) | Conteúdo internacional de wakeboard |
| **Victor Salmon** | [youtube.com/@VictorSalmonS](https://www.youtube.com/@VictorSalmonS) | Wakeboarder internacional |
| **JB O'Neill** | [youtube.com/@jboneill](https://www.youtube.com/@jboneill) | Wakeboarder internacional |

---

## Notas para o desenvolvimento do site

- Formato final: HTML + CSS estático (compatível com GitHub Pages sem Jekyll)
- O mapa deve ser exibido com legenda interativa ou numerada
- Separar visualmente as seções Regular e Goofy no mapa
- Paleta de cores: a definir com o autor
- Incluir intro pessoal do autor (a preencher)
