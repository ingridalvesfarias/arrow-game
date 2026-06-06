# 🏹 Arrow Game

Um jogo interativo e romântico onde o jogador controla um arco e flecha para acertar um alvo. Ao acertar ou errar, o jogo exibe mensagens temáticas animadas utilizando **GSAP (GreenSock Animation Platform)**.

## 🚀 Sobre o Projeto

O **Arrow Game** utiliza a manipulação de elementos **SVG** combinada com o poder da biblioteca **GSAP** para criar uma experiência de jogo fluida. O jogador deve clicar, arrastar para trás (mirar) e soltar para lançar a flecha, com cálculos de trajetória baseados em curvas de Bézier.

## 🛠️ Tecnologias Utilizadas

* **HTML5**: Estrutura SVG para o arco, flechas e alvo.
* **GSAP (TweenMax)**: Motor de animação principal para o movimento da flecha, o efeito elástico do arco e as animações de entrada/saída das mensagens.
* **MorphSVGPlugin**: Utilizado para gerenciar caminhos e trajetórias complexas da flecha.
* **JavaScript**: Lógica de jogo, incluindo detecção de colisões, cálculos trigonométricos para o ângulo do arco e manipulação de eventos de mouse.

## 🕹️ Como Jogar

1. **Mirar**: Clique e segure o botão do mouse para puxar a corda do arco.
2. **Lançar**: Arraste o mouse para ajustar o ângulo e a força do disparo, depois solte o botão para lançar a flecha.
3. **Objetivo**: Tente acertar o centro do alvo para ver uma mensagem especial!

## ⚙️ Configuração para Desenvolvimento

Como este projeto utiliza CDN para carregar as bibliotecas GSAP, basta abrir o arquivo `index.html` em qualquer navegador moderno. Não é necessário realizar instalação de dependências ou rodar um servidor local.

## 💡 Principais Funcionalidades

* **Física Visual**: Animação de estiramento do arco com `Elastic.easeOut`.
* **Detecção de Colisão**: O script calcula a interseção entre o segmento da flecha e o segmento do alvo em tempo real (`hitTest`).
* **Feedback Visual**: As mensagens de "Love You" ou "Miss You" aparecem animadas sobre a tela dependendo da precisão do seu tiro.

## Imagem do Projeto:
Acesse: https://arrow-game-zmzh.vercel.app/

<img src="img/imagem do projeto.png" alt="imagem do projeto">

---
*Criado com tecnologia web moderna.*
