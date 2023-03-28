# Meu-primeiro_vetor
Meu primeiro Vetor
Algoritmo "Meu primeiro Vetor"
// 
//  
// Descrição   : Aqui você descreve o que o programa faz! (função)
// Autor(a)    : Nome do(a) aluno(a)
// Data atual  : 27/03/2023

Var
nome:caractere
x: inteiro
notas: vetor [1..4] de real
vet: vetor [1..4] de real
media: real
nota: real


Inicio
Escreval ("Digite o nome do aluno")
leia (nome)
 para x de 1 ate 4 faca

     escreval("digite a nota: " , x)
leia(notas[x])
fimpara

para x de 1 ate 4 faca

escreval("nota ",x, " : ", notas [x])

fimpara
media<-(notas [1]+ notas [2]+notas [3]+notas [4])/4
Escreval(" A média é ", media)

Fimalgoritmo
