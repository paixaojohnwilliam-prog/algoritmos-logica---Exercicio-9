# algoritmos-logica---Exercicio-9

algoritmo "EmprestimoCreuza"
var
   emprestimo, juros, total: real
   parcelas, valorParcela: real

inicio
   Escreva("Qual o valor do empréstimo? R$ ")
   Leia(emprestimo)

   Escreva("Quantos % de juros? ")
   Leia(juros)

   Escreva("Em quantas parcelas deseja pagar? ")
   Leia(parcelas)


   total <- emprestimo + (emprestimo * juros / 100)

   valorParcela <- total / parcelas


   Escreval("O valor total com juros será: R$ ", total:8:2)
   Escreval("Você pagará ", parcelas, " parcelas de: R$ ", valorParcela:8:2)
   Fimalgoritmo
