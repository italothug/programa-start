# Aula 01 - Introdução

## 1.A

### Breakpoint

- Breakpoint
  - Acionado em uma linha quando apertado a tecla "F5"
  - Utilidade: Dar uma pausa no código na mesma linha que você colocou o ``breakpoint`` e só vai continuar se você apertar "F9"(Vai até o final ou até encontrar um outro ``breakpoint``) ou "F8"(Que vai parando nas próximas linhas)

## 1.B

### vetor / array

O comandor ``for / para`` nasceu pra ser utilizado junto com o ``vetor / array``

**vetores** são fundamentais para materias com estruturas de dados, banco de dados, entre outros

**vetores** tbm são tu utilizados dentro de outras variaveis como por exemplo dicionario ou lista dinâmica

[Exemplo](./imagens/ex-vetor.png)

## 1.C

### Exercicio de vetor

``Exercicio 1``: fazer um banco de dados de nomes e depois pesquisar por algum nome, depois retornar se achou ou não

[Exercicio](./imagens/exercicio1-vetor.png)

## 1.D

### Exercicio de vetor

``Exercicio 2``: fazer um vetor que receba a sequência de números de 0 -> 100 com intervalos de 10 e depois outro vetor com números de 100 -> 0 com intervalos de 10.

Minha [Resposta](./imagens/exercicio2-vetor-resposta.png)

Resposta que o professor queria
[Exercicio](./imagens/exercicio2-vetor.png)

``Exercicio 3``: fazer um vetor que receba a soma de 2 outros vetores em posições iguais. _(Por cima ainda criei um sistema que ficasse dando looping nas somas)_

Resposta:
[Parte1](./imagens/exercicio3-vetor-1.png)
[Parte2](./imagens/exercicio3-vetor-2.png)

## 1.E

Metódo bolha: usado para organizar um vetor em ordem crescente

``Exercicio 4``: Uma forma de organizar os vetores de forma crescente:

[Resposta](./imagens/exercicio4-vetor.png)

## 1.F

### Matrizes, é um vetor de mais dimensões

Escreval: escreve e pula linhas, Escreva: não pula

``Exercicio 5``: Fazer um menu para o cinema, onde aparecerá o layout das salas e cadeiras ocupadas e ter a opção de reservar.

Resposta
[Parte1](./imagens/exercicio5-vetor-cinema1.png)
[Parte2](./imagens/exercicio5-vetor-cinema2.png)

# Aula 02 - Procedimentos

## 2.A

Forma de conseguir variavel de escopo local

``Procedimento`` permite que exista variaveis apenas dentro de seus parâmetros e é uma forma de criar "Palavras chaves" personalizadas, que você possa atribuir valor

[Exemplo](./imagens/ex-procedimento.png)

## 2.B

O que é um função e a diferença de ``função`` para ``procedimento``

### Diferença:

- **Procedimento** processa algo de acordo com alguns dados de entrada

- **Função** tem a função de fazer esse processamento e retornar uma resposta

Exemplo de um procedimento funcionando
[Print](./imagens/ex-procedimento-funcao.png)

Exemplo de uma função funcionando
[Print](./imagens/ex-funcao-procedimento.png)

Sabendo sobre isso da função, é capaz tbm de combinar uma função em outra função
[Print](./imagens/ex-funcao-procedimento-2.png)

## 2.C

Aplicando **função** e **procedimento**

``Exercicio 6``: Receber 3 tamanhos de lados, verificar se faria um triângulo e dizer qual o tipo do triângulo.

Resposta

[Parte1](./imagens/exercicio6-funcao-e-procedimento-parte1.png)

[Parte2](./imagens/exercicio6-funcao-e-procedimento-parte2.png)

## 2.D

Aplicando **função** e **procedimento** parte 2

``Exercicio 7``: Registrar 5 clientes em uma lista e criar funções de ``registrar``, ``pesquisar`` e ``excluir``, usando os metódos de ``função`` e ``procedimento``

Resposta

[Parte1](./imagens/exercicio7-funcao-procedimento-parte1.png)

[Parte2](./imagens/exercicio7-funcao-procedimento-parte2.png)

[Parte3](./imagens/exercicio7-funcao-procedimento-parte3.png)

## 2.E

Aplicando **função** e **procedimento** parte 3

``Exercicio 8``: Fazer um código para registrar um gabarito, registrar a prova e verificar se a pessoa passou ou não.

Resposta
[Parte1](./imagens/exercicio8-funcao-procedimento-parte1.png)
[Parte2](./imagens/exercicio8-funcao-procedimento-parte2.png)
[Parte3](./imagens/exercicio8-funcao-procedimento-parte3.png)

# Aula 03 - Banco de Dados

## 3.A

Banco de dados: qualquer repositório que você guarda informações

Comando para criar tabela é:

``CREATE TABLE`` + NOME (Nome no plural)

``ID`` : Substitui os nomes das pessoas

``INT`` : Inteiro

``PRIMARY`` : Único

``AUTO-INCREMENT`` : Garante que você nunca vai precisar criar um ID

``VARCHAR`` : Mesma função de ``caractere`` e usasse ``(Algum número aqui)`` pra dizer que tem um máximo de letras que podem ser escritas

``NOT NULL`` : Obrigatório informar o nome

[Exemplo](./imagens/ex-bda.png)

## 3.B

Inserindo registro no banco de dados