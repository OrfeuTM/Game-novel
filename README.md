# Game-novel 🎮

> Uma Visual Novel / Game Novel interativa desenvolvida com tecnologias web fundamentais (HTML, CSS e JavaScript), focada em narrativa baseada em escolhas.

---

## 📖 Sobre o Projeto

Este projeto é uma **Visual Novel** interativa criada no formato **SPA (Single Page Application)**. A história passa-se em 2026 e gira em torno de dois irmãos gêmeos de 17 anos com personalidades opostas. 

O jogador faz a sua primeira grande escolha logo na tela inicial, definindo com qual dos dois irmãos irá jogar e vivenciando a narrativa sob diferentes perspetivas.

### 🌟 Destaques da Arquitetura:
- **Zero Reloads:** O jogo funciona inteiramente em apenas um ficheiro `index.html`, manipulando o DOM através de JavaScript.
- **Leve e Acessível:** Projetado para ser executado diretamente no navegador e hospedado no **GitHub Pages**.

---

## 👥 Personagens Principais

- **A Irmã (Gêmea):** Afrontosa, impulsiva e cabeça-quente. Tem um estilo visual marcante com pegada *streetwear/rock* (camiseta de banda, shorts rasgados e coturnos).
- **O Irmão (Gêmeo):** Frio, calculista e analítico. Um perfil investigador afrodescendente que utiliza a tecnologia (tablet digital) para examinar dados e resolver problemas de forma racional.

---

## 📁 Estrutura de Pastas

```text
meu-game-novel/
├── index.html                # Tela/Palco único do jogo (SPA)
├── README.md                 # Documentação do projeto
├── css/
│   └── style.css             # Estilização da interface, balões e botões
├── js/
│   ├── historia.js           # Objeto com o roteiro, cenas e opções de escolhas
│   └── script.js             # Lógica do jogo (troca de cenas e manipulação do DOM)
└── assets/                   # Recursos visuais do jogo
    ├── bg/                   # Cenários de fundo (ex: quarto compartilhado)
    └── personagens/          # Sprites e expressões dos gêmeos (menino e menina)