# Campo Minado em C

Jogo do campo minado em C usando Estruturas, Matrizes, Recursão...
<br>
<br>
# Executando: 
  1:> <b>  gcc CampoMinado.c -o CampoMinado</b> (enter) <br>
  2:> <b>  ./CampoMinado </b>  (enter) 
<br>
<br>
1. Regras do Jogo Campo Minado<br>
O Campo Minado é um jogo aparentemente simples de memória e raciocínio. O
objetivo do Campo Minado é revelar os quadrados vazios e com números, evitando
aqueles que escondem bombas. 
<br>
  • Você pode revelar o que existe em uma posição ou quadro digitando:<b> A i j </b> <br>
  A -> representa a opção Abir. <br>
  i -> indica a linha; <br>
  j -> indica a coluna. <br>
  <br><br>
Ao abrir, se você revelar uma bomba, perderá o jogo.
Em outro caso aparece um número, que indica o número total de bombas nos oito
quadrados que o cercam. Você pode usar esse número para ajudá-lo a deduzir
se é seguro revelar um quadrado. 
Quadrados com 0 indicam que não há bombas nos 8 quadrados que o cercam.  
<br>
Nesse caso pode acontecer:<br>
    a. você selecionou um espaço em branco (0): todos os espaços sem minas em volta são automaticamente revelados;

    b. você selecionou em um número: o número é revelado.
    
    c. você clicou em uma bomba: todas as posições são reveladas e você perdeu o jogo.
    
    Você ganha o jogo quando você revelar todas as posições que não são bombas.

@EdsonGreg @EPG @C
