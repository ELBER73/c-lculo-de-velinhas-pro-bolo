# c-lculo-de-velinhas-pro-bolo
Calculando a quantidade de velinhas para o bolo de aniversário

Algoritmo "Aniversario"
// Disciplina   : [Linguagem e Lógica de Programação no Visualg
// Descrição   : O programa dá exatamente a quantidade de velas necessárias para colocar no bolo de aniversário, com base na subtração do ano atual menos o 
ano de nascimento, resultando assim na idade.
// Autor(a)    : Lúcio Élber dos Santos
// Data atual  : 09/05/2022
Var
// Seção de Declarações das variáveis 
   ano_atual, ano_nasc, idade: Inteiro


Inicio
// Seção de Comandos, procedimento, funções, operadores, etc...
  Escreva ("#m que anos nós estamos? ")
  Leia (ano_atual)
  Escreva ("Em que ano você nasceu? ")
  Leia (ano_nasc)
  Idade <- ano_atual - ano_nasc
  Escreva ("Minha idade será ", idade)
  EscrevaL(" anos e eu terei ", idade, " velinhas no bolo.")
    

Fimalgoritmo
