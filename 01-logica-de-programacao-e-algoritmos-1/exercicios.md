# Exercicios usando os conceitos do VisuAlg

## 01 - Escreva um algoritmo que armazene o valor 10 em uma variável A e o valor 20 em uma variável B. A seguir (utilizando apenas atribuições entre variáveis) troque os seus conteúdos fazendo com que o valor que está em A passe para B e vice-versa. Ao final, escrever os valores que ficaram armazenados nas variáveis.

[Resposta](./imagens/ex1.png)

Fiz de uma outra forma, onde o usuário dá valor para as variáveis e no final os valores são trocados

## 02 - Escreva um algoritmo para ler as dimensões de um triângulo (base e altura), calcular e escrever a área do triângulo. Sabendo que para calcular a área devemos usar a fórmula a seguir;
[Fórmula](./imagens/questao2.png)

[Resposta](./imagens/ex2.png)

## 03 - Determinar se um número é par ou ímpar e positivo ou negativo;

[Resposta](./imagens/ex3.png)

## 04 - Ler três notas de um aluno, calcular a média e informar se ele foi aprovado (Média >= 7), reprovado (Média < 7) ou aprovado com louvor (Média = 10)

[Resposta](./imagens/ex4.png)

## 05  - Escrever um algoritmo que lê um número não determinado de valores para m, todos inteiros e positivos, um de cada vez. Se m for par, verificar quantos divisores possui e escrever esta informação. Se m for ímpar e menor do que 12 calcular e escrever o fatorial de m. Se m for ímpar e maior ou igual a 12 calcular e escrever a soma dos inteiros de 1 até numero lido.

## 06 - Escrever um algoritmo que leia informações sobre um grupo de 7 pessoas e calcule alguns dados estatísticos. Para cada pessoas do grupo deve ler o nome da pessoa, a altura, o peso e o sexo (“F” para feminino e “M” para o masculino). Calcular e escrever:
- A quantidade total de homens e mulheres e o percentual de cada.
- A média de peso das pessoas (somatório dos pesos de todas as pessoas pela quantidade de pessoas)
- O nome da pessoa mais alta.

Algoritmo "semnome"

Var
nome, sexo : caractere
altura, qtdEntrevistados : inteiro
peso, totalF, totalM, porcentagemM, porcentagemF, mPeso, totalPeso : real
Inicio
totalPeso <- 0
totalF <- 0
totalM <- 0
porcentagemM <- 0
porcentagemF <- 0
enquanto qtdEntrevistados < 4 faca
         Escreval("Por favor, informe as seguintes informações!")
         //Escreval("Nome")
         //leia(nome)
         //Escreval("Sexo(F ou M)")
         //leia(sexo)
         //Escreval("Altura")
         //leia(altura)
         Escreval("Peso")
         leia(peso)
         
         se sexo = "F" entao
            totalF <- totalF + 1
         fimse
         se sexo = "M" entao
            totalM <- totalM + 1
         fimse
         
         totalPeso <- totalPeso + peso
         qtdEntrevistados <- qtdEntrevistados + 1
fimenquanto

mPeso <- totalPeso / qtdEntrevistados
Escreval("A quantidade de pessoas entrevistadas é de",qtdEntrevistados," e a média de peso é de",mPeso)
//porcentagemM <- (totalM / qtdEntrevistados) * 100
//porcentagemF <- (totalF / qtdEntrevistados) * 100
//Escreval("A quantidade de mulher que fez a pesquisa é de",totalF,"(",porcentagemF,"%"," ) e a quantidade de homem é de",totalM,"(",porcentagemM,"%"," )")

Fimalgoritmo