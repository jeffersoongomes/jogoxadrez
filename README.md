# ♟️ Jogo de Xadrez Moderno (JavaScript puro)

Dê Play aqui para jogar ▶  https://jeffersoongomes.github.io/jogoxadrez/

> Um jogo de xadrez completo, responsivo e interativo, desenvolvido em **HTML5, CSS3 e JavaScript puro (Vanilla JS)**, sem
>  dependências externas ou frameworks pesados. Conta com lógica robusta de
>  regras oficiais, IA integrada e sintetizador de áudio via Web Audio API.

---

## 🚀 Demonstração das Funcionalidades

* **Lógica Completa de Xadrez:** 
  * Movimentação exata de todas as peças (Peão, Torre, Cavalo, Bispo, Rainha e Rei).
  * Capturas normais e visualização de peças capturadas em tempo real.
  * Regras especiais implementadas: **Roque** (pequeno e grande), **En Passant** e **Promoção de Peão**.
* **Validação de Xeque e Xeque-Mate:** 
  * Deteção automática de xeque (com alerta visual) e xeque-mate ou afogamento (*stalemate*).
  * Proteção do Rei (o jogador é impedido de realizar jogadas que deixem o seu próprio Rei em xeque).
* **Modos de Jogo:**
  * **2 Jogadores (Local / Pass & Play):** Jogue com um amigo no mesmo computador.
  * **Contra IA (Fácil):** Jogue contra uma inteligência artificial integrada.
* **Histórico de Jogadas:** Painel lateral que regista o histórico de movimentos realizados.
* **Design Responsivo:** Interface moderna inspirada em plataformas de código aberto, adaptável tanto a computadores quanto a dispositivos móveis.

---
## 🛠️ Tecnologias Utilizadas

* **HTML5** (Estrutura e elementos semânticos do tabuleiro)
* **CSS3** (Layouts em CSS Grid/Flexbox, variáveis e estilização moderna)
* **JavaScript (ES6+)** (Lógica do jogo, algoritmos de validação de posições, gestão de estado e Inteligência Artificial)

---

## 📂 Estrutura do Projeto

O projeto foi concebido de forma minimalista para ser executado de forma imediata em qualquer navegador:

```text
jogoxadrez/
│
└── index.html    # Contém toda a estrutura HTML, estilos CSS e lógica JS num único ficheiro otimizado
