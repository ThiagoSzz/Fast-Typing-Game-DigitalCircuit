# Fast Typing Game

## Sobre o jogo

O jogo é um jogo de digitação rápida feito em um circuito digital utilizando o [Wired Panda](https://gibis-unifesp.github.io/wiRedPanda/).

Você deve tentar digitar a sequência, que será gerada aleatoriamente, antes que o tempo acabe. Se você conseguir digitar antes de o tempo acabar, você ganha, senão, você perde.

Ao todo são 8 níveis de dificuldade. A cada nível, o tempo que você possui para digitar toda a sequência diminui, de forma a aumentar a dificuldade.

Este projeto foi desenvolvido como trabalho final da disciplina de Circuitos Digitais da CIC/UFRGS.

![image](https://user-images.githubusercontent.com/49589136/119418360-3ac1db00-bcce-11eb-901e-2de7ee9bb873.png)

## Circuito principal

O circuito principal é responsável por controlar os circuitos menores do jogo.

![Screenshot_1](https://github.com/ThiagoSzz/Fast-Typing-Game-DigitalCircuit/assets/49589136/e2d4379d-2eb0-441b-aae4-612bd86874da)

Além dele, foram utilizados: encoders 8x3, displays de 7 segmentos, multiplexadores 8x1, registradores de 8 bits, máquina de estados, entre outros.

![image](https://github.com/ThiagoSzz/Fast-Typing-Game-DigitalCircuit/assets/49589136/919c026e-969d-441e-8eab-c350ca7ea83b)

![image](https://github.com/ThiagoSzz/Fast-Typing-Game-DigitalCircuit/assets/49589136/1c456d2e-c6b1-453b-b14f-62a43bdf5422)

## Como jogar

1. Desligue o interruptor chamado "STOP" e ligue-o para randomizar a sequência de caracteres

![image](https://user-images.githubusercontent.com/49589136/119418601-bae84080-bcce-11eb-9e9b-cef2415c3f50.png)

2. Selecione o nível com os interruptores "LEVEL[2-0]" (lógica binária, o nível 1 refere-se a todos os interruptores desligados, o nível 5 refere-se aos interruptores LEVEL[2] e LEVEL[0] ativados, etc.)

![image](https://user-images.githubusercontent.com/49589136/119418800-35b15b80-bccf-11eb-9c7f-c787513fe064.png)

3. Copie os caracteres seguindo a ordem correta enquanto o último LED do temporizador (da esquerda para a direita) estiver aceso

![image](https://user-images.githubusercontent.com/49589136/119418874-66919080-bccf-11eb-9679-56603eb367b4.png)
![image](https://user-images.githubusercontent.com/49589136/119418975-9b9de300-bccf-11eb-843f-33991c71ba23.png)

4. Para inserir um caractere, use o teclado ou pressione os botões

![image](https://user-images.githubusercontent.com/49589136/119418925-8032d800-bccf-11eb-975c-a93cbad60652.png)

5. Se o caractere certo for inserido na ordem correta, um LED verde se acenderá

![image](https://user-images.githubusercontent.com/49589136/119418958-93de3e80-bccf-11eb-983a-0ee5a9d26058.png)

6. Se você terminar corretamente a cópia da sequência randomizada, você vence

![image](https://user-images.githubusercontent.com/49589136/119419032-ba9c7500-bccf-11eb-9e1d-a8274eb7672a.png)

7. Caso contrário, você perde

![image](https://user-images.githubusercontent.com/49589136/119419068-cd16ae80-bccf-11eb-92f6-1827716ee01b.png)

## Funcionalidades

- Seleção de níveis
- Clock-based
- Circuito sequencial
- Simulação em tempo real

## Tecnologias

![WiredPanda](https://img.shields.io/badge/WiredPanda-%23000.svg?style=for-the-badge&logoColor=white)

## Créditos
- Thiago Haab
