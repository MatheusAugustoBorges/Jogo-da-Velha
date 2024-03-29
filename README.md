## Jogo-da-Velha
Se trata de um jogo da velha simples desenvolvido em javascript.

# O jogo possui dois modos

- SinglePlayer: Usuário X Computador -> Opção 1 do Menu Principal
- Multiplayer: Usuário 1 X Usuário 2 -> Opção 3 do Menu Principal

 OBS 1 - Representação dos Jogadores

- Usuário 1 ou Usuário sempre serão representado por 'X'
- Computador ou Usuário 2 sempre serão representados por 'O'

# OBS 2 - Posições das Jogadas no Tabuleiro (Matriz)

- As linhas são representadas por números de 1 a 3 de cima para baixo
- As colunas são representadas por números de 1 a 3 de da esquerda para direita
Veja a representação a seguir:

% % % -> (1,1) (1,2) (1,3)
% % % -> (2,1) (2,2) (2,3)
% % % -> (3,1) (3,2) (3,3)

# OBS 4 - Jogadas Ganhadoras

- Para ganhar é necessário completar uma linha com jogadas de um mesmo jogador
Exemplo de Usuário 1 (Jogador 1) ganhando pela 3° linha.

% % %
% % %
X X X 

- Para ganhar é necessário completar uma coluna com jogadas de um mesmo jogador
Exemplo de Usuário 2 (Jogador 2) ganhando pela 3° linha.

% % O
% % O
% % O 

- Para ganhar é necessário completar a diagonal principal com jogadas de um mesmo jogador
Exemplo de Usuário 1 (Jogador 1) ganhando pela diagonal principal.

X % %
% X %
% % X

- Para ganhar é necessário completar a diagonal secundária com jogadas de um mesmo jogador
Exemplo de Usuário 2 (Jogador 2) ganhando pela diagonal secundária.

% % O
% O %
O % %

# OBS 5 - Para sair do Jogo da Velha

A partida deve ser finalizada e o jogo retornará para o menu principal
- A opção 3 fecherá o jogo da velha. . . 

