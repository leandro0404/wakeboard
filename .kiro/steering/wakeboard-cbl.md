# Canibal Wake Crew — Steering do Projeto

Este arquivo é a fonte de verdade do projeto. Contém contexto completo de conteúdo, decisões técnicas e estado atual do site. Leia antes de fazer qualquer alteração.

---

## Identidade

- **Nome do site:** Canibal Wake Crew
- **EST.:** 2026
- **Tagline:** Sports & Adventure
- **Logo:** `canibal.jpeg` — canibal surfando em prancha com âncoras e faixa
- **Criado em:** Novembro 2026
- **Repositório:** `git@github.com:leandro0404/wakeboard.git`
- **GitHub Pages:** `https://leandro0404.github.io/wakeboard/`
- **Branch principal:** `main`

---

## Contexto da pista

- **Pista:** CBL (Cable Board Lagoa)
- **Circuito:** fechado, sentido **horário**, 5 torres
- **Público-alvo:** iniciantes que estão aprendendo wakeboard do zero
- **Tom:** direto, prático — como um amigo que já roda te explicando
- **Bases cobertas:** Regular (pé esquerdo na frente) e Goofy (pé direito na frente)

---

## Stack técnica

- HTML5 + CSS3 puro — sem frameworks, sem dependências
- Mapa da pista em **SVG nativo** desenhado do zero
- Hospedado no **GitHub Pages** (branch `main`, raiz `/`)
- Para rodar local: `python3 -m http.server 8080`

## Arquivos do projeto

| Arquivo | Função |
|---------|--------|
| `index.html` | Página única do site com todas as 8 seções |
| `style.css` | Estilos — paleta azul claro/branco, responsivo |
| `canibal.jpeg` | Logo do grupo — usada no hero e como marca d'água de fundo |
| `pista-bg.svg` | SVG limpo do circuito — cabo, torres e seta horária |
| `wake_cbl_mapa_ paint.png` | Rascunho original feito no Paint (referência) |
| `README.md` | Documentação do projeto no GitHub |

---

## Visual e design

- **Paleta:** branco + azul claro (`#1a6fbb`, `#f0f7ff`, `#1a2e44`)
- **Hero:** imagem `canibal.jpeg` como fundo com gradiente escuro translúcido
- **Marca d'água:** `canibal.jpeg` repetida em toda a página (780px, overlay rgba 0.60)
- **Seções:** fundo semi-transparente (rgba 75%) para a marca d'água aparecer
- **Responsivo:** breakpoint em 600px

---

## Estrutura das 8 seções

### 1. Equipamento para começar
Prancha (tamanho por peso), colete obrigatório, rope e handle, capacete, lycra.

### 2. Primeiros passos fora da água
Regular vs Goofy, stance, como segurar o handle, posição no dock start.

### 3. Dock Start
Agachar, deixar o cabo puxar, olhar pra frente, prancha plana nos primeiros metros.

### 4. Primeiras voltas
Cabo tenso, absorver curvas com joelhos, olhar pro próximo ponto, não resistir nas polias.

### 5. Mapa da pista CBL — SVG
Mapa desenhado em SVG com 5 torres (boias laranjas), cabo tracejado horário e 8 obstáculos posicionados.

**Sequência dos obstáculos na reta do topo (após dock start, da esquerda para direita):**
1. Kicker 1 — abaixo do cabo (lado direito da pista)
2. Kicker 2 — acima do cabo (lado esquerdo da pista)
3. Flat Bar 1 — abaixo do cabo
4. Flat Bar 2 — acima do cabo

**Obstáculos na lateral esquerda:**
- Incliner — rampa lateral, praticamente sem cavada

**Obstáculos na base (sentido horário, torre 4 → torre 5):**
- Transfer — acima do cabo (lado direito para quem vem), próximo torre 4
- Rooftop — abaixo do cabo (lado esquerdo para Regular), próximo torre 4
- Fibonat — abaixo do cabo, entre torre 4 e torre 5

**Torre 3 (ponta direita):**
- Jump/Olie — obstáculo simples para treinar olie

**Níveis:**

| Obstáculo | Nível |
|-----------|-------|
| Dock Start | Entrada |
| Incliner | Iniciante |
| Flat Bar ×2 | Iniciante |
| Kicker ×2 | Iniciante/Médio |
| Jump/Olie | Iniciante/Médio |
| Transfer | Médio |
| Fibonat | Médio |
| Rooftop | Avançado |

### 6. Técnica — curvas e cavadas

**Curvas no sentido horário:**

| Base | Curva | O que fazer |
|------|-------|-------------|
| Regular | Abre (esquerda) | Calcanhar — heelside |
| Regular | Fecha (direita) | Ponta dos pés — toeside |
| Goofy | Abre (direita) | Ponta dos pés — toeside |
| Goofy | Fecha (esquerda) | Calcanhar — heelside |

**Cavadas:**
- Curvas normais: suave, joelhos absorvendo
- Antes de obstáculo: solta a cavada ~5 metros antes (iniciante), entra neutro. Cavadas fortes são para experientes
- Incliner: praticamente não cava — só direciona a prancha
- Kicker: pequena cavada heelside antes, neutro na subida
- Flat bar: cavada progressiva bem leve partindo de baixo do cabo, entra neutro — a posição debaixo do cabo é a referência fixa
- **Uma mão ao entrar em obstáculos:** soltar uma mão alinha o corpo para a margem, evita rotação dos ombros. Duas mãos puxam os ombros para frente e desequilibram. Com uma mão e joelhos flexionados o equilíbrio é mais fácil de recuperar

### 7. Macetes gerais
- Caia de lado, nunca de frente
- Se caiu e tem alguém vindo: afunde a cabeça dentro da água
- Antes do kicker: olha atrás do obstáculo, se alguém caiu não entra
- Quem caiu fica na lateral, espera o cabo afundar antes de nadar
- Ao passar no dock start com alguém saindo: vai pro kicker se não estiver marolado, evita a flat bar — tranco de quem inicia pode folgar o cabo
- Nas curvas use heel ou toe conforme a direção — prancha reta pode estilinguar pelo cabo ou bater de nuca (Regular) ou de cara (Goofy)
- Na dúvida num obstáculo: primeira vez sem trick, só passar por cima

### 8. Canais recomendados

| Canal | URL | Nota |
|-------|-----|------|
| CBL | [Playlist iniciante](https://www.youtube.com/watch?v=15KZ-swzWE8&list=PLI5Vcra_PrsWc5NLL2FpJEGcDaA4E3cNR) | Único canal brasileiro 🇧🇷 |
| Julia Rick | [youtube.com/@JuliaRick](https://www.youtube.com/@JuliaRick) | Wakeboarder brasileira |
| The Peacock Brothers | [youtube.com/@ThePeacockBrothers](https://www.youtube.com/@ThePeacockBrothers) | Internacional |
| Victor Salmon | [youtube.com/@VictorSalmonS](https://www.youtube.com/@VictorSalmonS) | Internacional |
| JB O'Neill | [youtube.com/@jboneill](https://www.youtube.com/@jboneill) | Internacional |

---

## Histórico de decisões importantes

- Mapa feito em SVG nativo (não imagem) para ser editável e responsivo
- Imagem original do Paint (`wake_cbl_mapa_ paint.png`) mantida como referência mas não exibida no site
- Logo `canibal.jpeg` usada como fundo em duas formas: hero (cover com gradiente) e marca d'água na página toda (repeat, 780px, overlay 0.60)
- Seções com fundo semi-transparente para a marca d'água aparecer por baixo
- Curvas Regular/Goofy corrigidas: no sentido horário, Regular abre no calcanhar (não na ponta do pé)
- Distância antes de obstáculo: 5 metros para iniciante (não 2m)
- Macetes revisados — removidas dicas sem sentido para iniciante
- Branch renomeada de `master` para `main`
- Tag `v1.0.0` criada no commit de lançamento
