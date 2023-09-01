﻿# PONTIFÍCIA UNIVERSIDADE CATÓLICA DE MINAS GERAIS 
 
Disciplina: Algoritmos e Estruturas de Dados
Lista de Exercícios 
1) Escreva um método recursivo que receba dois inteiros positivos a e n e calcule a
n
.
( )
 
2) Escreva um método recursivo que receba como parâmetro dois números inteiros positivos m e n, e 
retorne a soma dos números no intervalo [m,n].
Exemplo: m= 4 e n=7, 
soma = 4 + 5 + 6 + 7 = 22
3) Implemente um método recursivo para converter um número decimal para binário (isto é, converter um 
número do Sistema Decimal para o Sistema Binário). O método deve receber como parâmetro um 
número decimal positivo e deve imprimir na tela esse número convertido para binário (Obs: o método 
não deve ter retorno, deve ser void). 
Uma maneira simples de resolver o problema é dividir o número decimal sucessivamente por 2 e pegar 
o resto da i-ésima divisão, da direita para esquerda. 
Exemplo1 - Para o número 12 temos: 
12/2 = 6, resto 0
6/2 = 3, resto 0
3/2 = 1, resto 1
1/2 = 0, resto 1
Portanto, o número 12 em binário é 1100
Exemplo 2 - Para o número 8 temos:
8/2 = 4, resto 0
4/2 = 2, resto 0
2/2 = 1, resto 0
1/2 = 0, resto 1
Portanto, o número 8 em binário é 1000
4) O máximo divisor comum (MDC) de dois números inteiros x e y pode ser calculado usando-se uma 
definição recursiva: 
MDC(x, y) = MDC(x − y, y) se, x > y . 
Além disso, sabe-se que: 
MDC(x,y) = MDC(y,x)
MDC(x,x) = x
Exemplo: 
MDC(10,6) = MDC(4,6) = MDC(6,4) = MDC(2,4) = MDC(4,2) = MDC(2,2) = 2 
Implemente um método recursivo que receba como parâmetro dois números inteiros, calcule e retorne 
o MDC de x e y
