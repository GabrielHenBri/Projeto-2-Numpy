# Projeto-2-Numpy  
## Jogo da Velha (Tic-Tac-Toe)

### Descrição
Este é um jogo da velha simples feito para rodar no terminal, utilizando a biblioteca **NumPy** para representar o tabuleiro como uma matriz 3x3. Dois jogadores se revezam para colocar suas peças até que um deles vença ou ocorra um empate.

### Funcionalidades
- Cria um tabuleiro 3x3 usando arrays do NumPy.
- Permite entrada dos jogadores (1 e 2) via terminal.
- Verifica automaticamente vitória por linhas, colunas ou diagonais.
- Detecta empate caso todas as posições estejam ocupadas sem vencedor.
- Exibe o tabuleiro atualizado a cada rodada.

### Requisitos
- Python 3.x  
- Biblioteca NumPy

### Instalação
1. Clone este repositório ou copie o código para sua máquina.  
2. Instale a biblioteca NumPy, se ainda não tiver:

```bash
pip install numpy
```

###Como Jogar

O jogo irá mostrar o tabuleiro com espaços vazios (representados por " ").

Jogadores se alternam para jogar, informando:

Linha (0, 1 ou 2)

Coluna (0, 1 ou 2)

Caso o jogador escolha uma posição inválida ou ocupada, será solicitado que escolha novamente.

O jogo termina quando:

Um jogador alinha 3 peças (vitória)

Todas as posições estão ocupadas (empate)

```Exemplo de Execução

  |   |  
--------
  |   |  
--------
  |   |  

Jogador 1, escolha a linha (0, 1, 2): 0  
Jogador 1, escolha a coluna (0, 1, 2): 0  

1 |   |  
--------
  |   |  
--------
  |   |  

...
Parabéns, jogador 2 venceu!
