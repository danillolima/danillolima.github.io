---
layout: default
---

# Listas encadeadas 


1. Escreva sobre as vantagens e as desvantages da estrutura de vetor em relação a estrutura
de lista simplesmente encadeada. Justique os argumentos.  
R:   
  Vantagens do vetor:  
  A estrututura de vetor pode representar N elementos do mesmo tipo.  
  Mais rápido, já que o espaço é alocado na inicialização.  
  Fácil para implementar e usar.  
  Desvantagens do vetor:  
  Tamanho fixo, não podemos mudar o tamanho após a alocação inicial.  
  Operação de remover e mover determinado elemento pode ser custoso.  
  Representar apenas um tipo de dado por elemento.  

  Vantagens da lista:  
  Podem conter os tipos de dados padrões e tipos de dados abstratos(TAD).  
  Inserção entre elementos mais eficiente.  
  Desvantagens da lista:  
  Acesso sequêncial, precisa percorrer a lista para achar determinado elemento.  
  Gasto de memória, ponteiros precisam de espaço extra para serem armazenados.  
  Acesso transversal, se a lista for simplemente encadeada, voltar do último nó para os predecessores é uma tarefa difícil.  

2. Implemente a operação “reverte” que irá reverter os elementos de uma lista encadeada
e que devolve o primeiro elemento da lista reversa.

3. Implemente a operação de “ordenar” uma lista.

4. Escreva uma função para contar a quantidade de elementos em uma lista circular, a
função recebe o ponteiro para algum nó desta lista.

5. Escreva uma função que conta a quantidade de nós que esta entre um nó t e um nó x
de uma lista circular.

6. Escreva uma função que insere uma lista linear dentro de uma lista circular a partir
de um nó t da lista circular.

7. Uma letra significa para enfilar a letra, um asterisco significa para desenfilar. Assuma
a seguinte sequência:  
F A C * I L * * * *  
Fornece a sequência de valores devolvido pelas operações de desenfilar quando as operações são executadas com a fila inicialmente vazia.

8. Calculadora: Escreva um programa que recebe uma string com uma expressão na
notação infixa e calcula o teu valor. Por exemplo, se o teu programa receber ((1 +
2) * (3 + 4)) ele deve imprimir na tela o valor 21. Assuma que a expressão tenha
apenas números de 0 até 9 e também apenas as operações de soma e multiplicação.

9. Melhore o teu programa para que seja possível receber outros números inteiros e
operações de divisão e também subtração.  

10. Suponha que os elementos de um vetor v são do tipo GPS e que cada GPS ocupa 24
bytes no seu computador. Se v[0] tem endereço 1024, qual o valor de v + 5 ?  

11. Considere o trecho de código abaixo:  
double a[5] = {12.0,24.0,3.2,6.4,12.8};  
double *v = a;  
• Explique a diferença entre v + 1 e v[1].  

12. Qual a sequência de comandos free para liberar a memória alocada pelas chamadas
de malloc do trecho de código abaixo ?  
double ***v;  
int i = 0;  
int j = 0;   
v = (double ***) malloc (sizeof(double **) * 5);  
for (i = 0; i < 5; i++){  
v[i] = (double **) malloc (sizeof(double*) * 4);  
for(j = 0; j < 4; j++) {   
v[i][j] = (double *) malloc(sizeof(double) * 3);  
}  
}  

13. Escreva um breve resumo de como e quando podemos utilizar a −> em um programa
na linguagem C. Dê alguns exemplos.  

14. O que é “Tipo Abstrato de Dado” ? Forneça um exemplo de TAD.  
15. Descreva quatro diferentes formas de se implementar lista encadeadas.  
16. Implemente uma função que imprime apenas os elementos pares de uma
lista circular.  
17. Implemente uma função que verifica se uma expressão matemática esta
com os parênteses e colchetes bem encaixados ou não. Por exemplo, a expressão (1 +
2 ∗ (3 + [4 + 5])) possui os parênteses e colchetes bem encaixados, mas a expressão
(1 + ((2 ∗ 3] não tem os parênteses e colchetes bem encaixados.  
18. Implemente a operação de enfilar utilizando uma lista simplesmente encadeada
sem cabeça célula.  
19. Implemente a operação de push utilizando uma lista simplesmente encadeada
com cabeça célula.  
