# Pygame Basics

Este repositório contém um exemplo de movimentação de um sprite animado dentro de uma janela utilizando a biblioteca Pygame. O código base foi elaborado para permitir que o sprite se movimente livremente em qualquer direção, sem nunca sair da tela. Além disso, o sprite pode contornar o botão de sair, evitando ser coberto por ele.

## Funcionalidades

- **Movimentação livre**: O sprite pode ser movido em todas as direções (cima, baixo, esquerda e direita) dentro da janela, sem sair da área visível da tela.
- **Contorno do botão de sair**: O sprite é capaz de contornar o botão de sair da janela, garantindo que ele não seja coberto pelo botão e tenha espaço para se mover.

## Como rodar o projeto

1. Certifique-se de ter o Python e o Pygame instalados em seu ambiente.
   
   Caso não tenha o Pygame, instale-o com o seguinte comando:
   ```bash
   pip install pygame
   ```

2. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/Pygame-Basics.git
   ```

3. Navegue até o diretório do repositório:
   ```bash
   cd Pygame-Basics
   ```

4. Execute o código:
   ```bash
   python main.py
   ```

## Descrição do código

- O código principal se encontra no arquivo `main.py`, onde a janela Pygame é criada e configurada.
- A movimentação do sprite é controlada pelas teclas de direção do teclado, e a lógica de contorno do botão de sair foi implementada para garantir que o sprite nunca o sobreponha.