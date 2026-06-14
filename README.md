#### Imagens do Jogo

![Gameplay](assets/projeto%20flappy%20bird1.jpeg)
![Game contagem ](assets/projeto%20flappy%20bird2.jpeg)

#### Flappy Bird em Java (Swing)

Projeto inspirado no clássico Flappy Bird, desenvolvido em Java com a biblioteca Swing.  
O objetivo foi praticar lógica de jogos 2D, manipulação de eventos, física simples e renderização gráfica.

#### Demonstração

####  Gameplay
![Gameplay](assets/projeto%20flappy%20bird1.jpeg)

####  Desenvolvimento do jogo
![Contagem de pontuações](assets/projeto%20flappy%20bird2.jpeg)

#### Funcionalidades

- Controle do pássaro com tecla **SPACE**
- Sistema de gravidade e física simples
- Geração automática de obstáculos (pipes)
- Sistema de pontuação em tempo real
- Detecção de colisão (pássaro vs canos e chão)
- Reinício automático após Game Over
- Loop de jogo em 60 FPS
- Renderização de imagens com Java Swing

Como o jogo funciona

O jogo é baseado em um loop contínuo utilizando `Timer` do Java:

- Atualização da tela a 60 FPS
- Criação de pipes a cada 1.5 segundos
- Aplicação de gravidade no pássaro
- Movimento dos obstáculos para a esquerda
- Sistema de colisão baseado em bounding box (AABB)
- Controle de estado com variável `gameOver`


####  Tecnologias utilizadas

- Java
- Swing (JFrame, JPanel)
- AWT Graphics
- Java Timer
- Programação orientada a objetos (POO)


####  Estrutura do projeto


Flappy-Bird/
├── src/
│ ├── App.java
│ ├── FlappyBird.java
├── assets/
│ ├── flappybird.png
│ ├── flappybirdbg.png
│ ├── toppipe.png
│ ├── bottompipe.png
├── README.md

#### Como executar o projeto

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/Flappy-Bird.git
Abra o projeto em sua IDE (IntelliJ, Eclipse ou VS Code)

Execute a classe principal:
App.java
Controles
SPACE → faz o pássaro pular
Evite colidir com os canos

Tente alcançar a maior pontuação possível

#### Destaques técnicos
Uso de classes internas (Bird e Pipe)
Sistema de spawn dinâmico de obstáculos
Controle de estado do jogo
Reinício automático sem reiniciar a aplicação
Renderização manual com paintComponent
Estrutura simples e eficiente para jogo 2D
 Objetivo do projeto

Este projeto foi desenvolvido com foco em aprendizado prático, demonstrando:

Lógica de programação
Manipulação de eventos em Java
Estrutura de jogos 2D simples
Controle de física básica
Programação orientada a objetos

 Autor : https://github.com/joseluizp/Flappy-Bird.git

Projeto desenvolvido para fins de estudo e portfólio.
