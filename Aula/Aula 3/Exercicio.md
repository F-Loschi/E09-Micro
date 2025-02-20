1) Analise o programa a seguir e responda:

a) Indique quais partes são:

  * Programa principal:
    * Tudo que estiver dentro da main
  * Declaração de variável global:
    * unsigned char cont=0
  * Chamada de função:
    * delayms(1000);
  * Loop infinito:
    * for(;;)

b) Qual o limite de armazenamento da variável cont?:
* 256 bit

c) Qual o valor carregado em cont a cada vez que o loop é executado?: 
* A variável + 1

d) Qual a relação que existe entre os valores de cont e P1?: 
* Os valores são invertidos com o operador (~)
---
2) Analise as estruturas condicionais abaixo e responda:

a) Para quais valores de "a" a variável j será igualada a zero?
* Para valores entre 0 <= a <=10 ou quando a ou b é igual zero

b) Para quais valores de "a" a variável j será incrementada?
* Quando a é maior que 10 ou quando ambos a e b são maiores que 0

c) Seria viável substituir essas estruturas "if" por "switch"?
* Não, pois como os casos de um switch aceitam apenas valores fixos, teríamos que ter infinitos casos de um switch
