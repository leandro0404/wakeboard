# 🏄 Canibal Wake Crew — Guia para Iniciantes

> Site estático feito para quem está começando no wakeboard no CBL, com dicas práticas de quem aprendeu lá dentro.

**[🌐 Acessar o site](https://leandro0404.github.io/wakeboard/)**

---

## Sobre o projeto

A ideia nasceu da necessidade de reunir em um lugar só as informações que todo iniciante precisa mas que ninguém explica de forma organizada — desde o equipamento até os macetes de como se comportar na pista.

O foco é o **CBL (Cable Board Lagoa)**, circuito fechado no sentido horário com 5 torres. O conteúdo cobre as duas bases (**Regular** e **Goofy**) e é escrito no tom direto de quem já rodou lá e aprendeu na prática.

---

## Conteúdo

| Seção | O que cobre |
|-------|-------------|
| **Equipamento** | Prancha, colete, rope, capacete, lycra |
| **Primeiros passos** | Regular vs Goofy, stance, como segurar o handle |
| **Dock Start** | Como sair da beira sem tomar caldo logo de cara |
| **Primeiras voltas** | Cabo tenso, curvas, olhar para frente |
| **Mapa da pista** | SVG interativo com os 8 obstáculos posicionados e dicas por torre |
| **Técnica** | Curvas heel/toe por base, cavadas, uma mão no obstáculo |
| **Macetes** | Segurança, etiqueta da pista, dicas que só vêm com experiência |
| **Canais** | Referências no YouTube para continuar evoluindo |

---

## Mapa SVG da pista

O mapa foi desenhado do zero em SVG com base no layout real do CBL:

- **5 torres** (boias laranjas) com dica de passagem em cada curva
- **Trajeto tracejado** no sentido horário
- **8 obstáculos** posicionados: Dock Start, Incliner, Kicker ×2, Flat Bar ×2, Transfer, Fibonat, Rooftop e Jump/Olie
- Legenda com nível de dificuldade de cada obstáculo

---

## Canais recomendados

- [CBL — Playlist iniciante](https://www.youtube.com/watch?v=15KZ-swzWE8&list=PLI5Vcra_PrsWc5NLL2FpJEGcDaA4E3cNR) 🇧🇷
- [Julia Rick](https://www.youtube.com/@JuliaRick)
- [The Peacock Brothers](https://www.youtube.com/@ThePeacockBrothers)
- [Victor Salmon](https://www.youtube.com/@VictorSalmonS)
- [JB O'Neill](https://www.youtube.com/@jboneill)

---

## Stack

- HTML5 + CSS3 puro — sem frameworks, sem dependências
- SVG nativo para o mapa da pista
- Hospedado no **GitHub Pages**

---

## Rodar localmente

Não precisa de build. Só abrir o `index.html` no navegador ou usar um servidor local:

```bash
cd "wakeboard site"
python3 -m http.server 8080
# acessa http://localhost:8080
```

---

*Canibal Wake Crew — EST. 2023 · Sports & Adventure · Novembro 2026*
