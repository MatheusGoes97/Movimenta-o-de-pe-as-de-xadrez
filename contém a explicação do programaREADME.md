# Movimenta-o-de-pe-as-de-xadrez (iniciante) (aventureiro) (mestre)
Atividade para testar o conhecimento

Como o Programa Funciona:
Torre (usando for):
Move-se em linha reta (horizontal ou vertical), neste caso, simulado 5 movimentos para a direita, usado for porque sabemos exatamente quantas casas vai mover (5).

Bispo (usando while):
Move-se apenas na diagonal, simulado 5 movimentos na diagonal superior direita, usando while para demonstrar outra estrutura de repetição, imprime duas direções combinadas ("Cima, Direita")

Rainha (usando do-while):
Pode mover-se em qualquer direção (como torre + bispo), simulado 8 movimentos para a esquerda, usando do-while para garantir que execute pelo menos uma vez.

Como Executar:
Copie o código para um arquivo xadrez.c
Compile com: gcc xadrez.c -o xadrez
Execute com: ./xadrez

# Nível aventureiro:

Explicação do Código:
Estrutura do Programa:Foca exclusivamente no movimento do cavalo, utiliza constantes para definir a quantidade de movimentos, implementa loops aninhados conforme exigido.

Loops Aninhados:
Loop externo (for): Controla os 2 movimentos para baixo.
Loop interno (while): Controla o 1 movimento para esquerda.
O movimento lateral só ocorre após completar os movimentos verticais.

Atendimento aos Requisitos:
Uso obrigatório de um for e um while aninhados.
Variáveis descritivas e constantes para valores fixos.

# Explicação do Funcionamento nível avançado:
1. Recursividade (Torre, Bispo e Rainha)
Cada peça tem sua própria função recursiva, a função chama a si mesma até atingir a condição de parada (casas <= 0).

Exemplo para Torre:
2. Loops Complexos para o Cavalo
Usa dois loops for aninhados:
Loop externo controla 2 movimentos verticais ("Cima").
Loop interno controla 1 movimento horizontal ("Direita").
O movimento horizontal só ocorre após completar os verticais.

3. Bispo com Loops Aninhados
Implementação alternativa com loops:.
Loop externo para controle vertical (5 iterações).
Loop interno para controle horizontal (1 iteração por movimento diagonal).

Como Executar
Copie o código para um arquivo xadrez_avancado.c
Compile com: gcc xadrez_avancado.c -o xadrez
Execute com: ./xadrez
