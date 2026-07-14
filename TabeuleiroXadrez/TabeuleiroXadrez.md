Tabuleiro de xadrez editável para Super Chip.

#  MOVIMENTAÇÃO DO CURSOR:
#    W        - Move para cima
#    S        - Move para baixo
#    A        - Move para a esquerda
#    D        - Move para a direita
#
#  JOGADA NORMAL:
#    E        - Seleciona uma peça da cor do jogador atual
#              Pressione novamente E em uma casa de destino válida
#              (vazia ou com peça adversária) para mover.
#              Pressionar E na mesma peça cancela a seleção.
#
#  EDIÇÃO DO TABULEIRO (não altera o turno):
#    Q        - Apaga a peça na casa sob o cursor
#    Z        - Coloca/avança peça BRANCA na casa:
#               Casa vazia ou peça preta -> insere peão branco
#               Peça branca -> avança para a próxima peça branca
#               (ciclo: peão -> torre -> cavalo -> bispo -> dama -> rei)
#    X        - Coloca/avança peça PRETA na casa:
#               Casa vazia ou peça branca -> insere peão preto
#               Peça preta -> avança para a próxima peça preta
#               (ciclo: peão -> torre -> cavalo -> bispo -> dama -> rei)
#
#  CONTROLE DE TURNO:
#    C        - Alterna o turno entre jogador 1 (brancas) e jogador 2 (pretas)
#               Útil para passar a vez, corrigir o turno ou durante a
#               promoção de peões.
#
#  INDICADOR VISUAL DE TURNO:
#    Canto superior direito da tela:
#      Quadrado cheio (branco) -> vez das brancas (jogador 1)
#      Moldura (contorno)      -> vez das pretas  (jogador 2)
#
#  OBSERVAÇÕES:
#    - Não há regras de movimento implementadas; as peças podem ser
#      posicionadas livremente.
#    - Capturas são permitidas se o destino contiver peça adversária.
#    - Para promover um peão, mova-o até a última fileira, use 'Q' para
#      removê-lo e 'Z' ou 'X' para inserir a nova peça, ou então use
#      'Z' / 'X' diretamente sobre ele para ciclar até a peça desejada.
#    - O cursor pisca para indicar sua posição.
#    - Uma casa selecionada é destacada com um marcador especial.
