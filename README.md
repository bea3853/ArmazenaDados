# ArmazenaDados
Em Portugol,  um programa que armazene dados (nome, função, idade, sexo e salário) de 5 funcionários

algoritmo "CadastrodeFuncionarios_BeatrizALves"
var
   nome:vetor[1..5] de caracter
   sexo:vetor[1..5] de caracter
   idade:vetor [1..5]de inteiro
   profissao:vetor[1..5] de caracter
   salario:vetor[1..5] de real
   i:inteiro


inicio

   escreval("Informe os dados de acordo com a ordem")

   escreval("Após digitar um dado, clique em enter e digite o próximo.")
   escreval("  ")
   escreval("1ºnome, 2ºsexo, 3ºidade, 4ºprofissão, 5ºsalário:")
   para i de 1 ate 5 faca
      escreval("  ")
      escreval ("DADOS DO FUNCIONÁRIO - ", i)
      leia(nome[i], sexo[i], idade[i], profissao[i], salario[i])

   fimpara
   escreval ("Término da entrada de dados")

   escreval("-----------------------------")

   escreval ("Leitura da matriz e apresentação de dados")
   escreval("nome, sexo, idade, profissão, salario")

   para i de 1 ate  5 faca

      escreval(nome[i]:8, sexo[i], idade[i], profissao[i], salario[i]:14)


   fimpara

fimalgoritmo
