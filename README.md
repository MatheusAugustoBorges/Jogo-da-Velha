# Jogo-da-Velha
Se trata de um jogo da velha desenvolvido em javascript.

# Rodando o Jogo da Velha. . . 

- Para rodar o jogo, basta clonar esse reposítório e executar o arquivo 'jogo-da-velha.html'.
- Para execução do arquivo, após clonar o reposítório você pode abrir a pasta baixada e executar em seu navegador o arquivo acima. 

# Modos de Jogo da Velha

- SinglePlayer: Usuário X Computador -> Opção 1 do Menu Principal
- Multiplayer: Usuário 1 X Usuário 2 -> Opção 2 do Menu Principal

# Representação dos Jogadores

- Usuário 1 ou Usuário sempre serão representado por 'X'
- Computador ou Usuário 2 sempre serão representados por 'O'

# Posições das Jogadas no Tabuleiro (Matriz)

- As linhas são representadas por números de 1 a 3 de cima para baixo
- As colunas são representadas por números de 1 a 3 de da esquerda para direita <br/>
Veja a representação a seguir:

% % % -> (1,1) (1,2) (1,3) <br/>
% % % -> (2,1) (2,2) (2,3) <br/>
% % % -> (3,1) (3,2) (3,3) <br/>

# Jogadas Ganhadoras

- Para ganhar é necessário completar uma linha com jogadas de um mesmo jogador <br/>
Exemplo de Usuário 1 (Jogador 1) ganhando pela 3° linha.

% % % <br/>
% % % <br/>
X X X <br/>

- Para ganhar é necessário completar uma coluna com jogadas de um mesmo jogador <br/>
Exemplo de Usuário 2 (Jogador 2) ganhando pela 3° linha.

% % O <br/>
% % O <br/>
% % O <br/>

- Para ganhar é necessário completar a diagonal principal com jogadas de um mesmo jogador <br/>
Exemplo de Usuário 1 (Jogador 1) ganhando pela diagonal principal.

X % % <br/>
% X % <br/>
% % X <br/>

- Para ganhar é necessário completar a diagonal secundária com jogadas de um mesmo jogador <br/>
Exemplo de Usuário 2 (Jogador 2) ganhando pela diagonal secundária.

% % O <br/>
% O % <br/>
O % % <br/>

# Para sair do Jogo da Velha

A partida deve ser finalizada e o jogo retornará para o menu principal <br/>
- A opção 3 fecherá o jogo da velha. . . 

