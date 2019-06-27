# Campo-MInado-em-C
Jogo do campo minado em C usando Estruturas, Matrizes, Recursão...

1. Regras do Jogo Campo Minado
O Campo Minado é um jogo aparentemente simples de memória e raciocínio. O
objetivo do Campo Minado é revelar os quadrados vazios e com números, evitando
aqueles que escondem bombas. 

  • Você pode revelar o que existe em uma posição ou quadro digitando: A i j
  A -> representa a opção Abir.
  i -> indica a linha;
  j -> indica a coluna. 
  
Ao abrir, se você revelar uma bomba, perderá o jogo.
Em outro caso aparece um número, que indica o número total de bombas nos oito
quadrados que o cercam. Você pode usar esse número para ajudá-lo a deduzir
se é seguro revelar um quadrado. 
Quadrados com 0 indicam que não há bombas nos 8 quadrados que o cercam.  

Nesse caso pode acontecer:
    a. você selecionou um espaço em branco (0): todos os espaços sem minas em volta são automaticamente revelados;

    b. você selecionou em um número: o número é revelado.
    
    c. você clicou em uma bomba: todas as posições são reveladas e você perdeu o jogo.
    
    Você ganha o jogo quando você revelar todas as posições que não são bombas.
