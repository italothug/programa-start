# Aula 01 - Boas Vindas

## Comandos
- ``System.out.println();`` = ``Escreval()`` do Portugol
- ``// Comentário de linha``
- ``/* Comentário de bloco */``
- ``/** Comentário de documentação */``
  - É um comentário que sai expresso em um papel, comentário usado muitas vezes em empresas com outras pessoas que precisam ler seu código.
- ``import java.util.Scanner;`` 
  - Leitor / Comando de entrada e saida do **JAVA**
- ``Scanner leitor = new Scanner(System.in);``
  - Forma de criar um leitor para dentro do **JAVA**
- ``var nome = leitor.nextVar();`` = ``Leia`` do Portugol
  - Forma de ler o próximo dado que se encaixaria naquela variavel
- Tipos de ``Var``
  - `int` 
    - Variavel de número INTEIRO
  - ``float`` e ``double`` 
    - Variaveis de número REAL
    - Diferença:
      - O double tem mais precisão: pode representar mais casas decimais ou números inteiros maiores;
      - O double ocupa 32 bits a mais que o float (o dobro do espaço);
      - Dependendo do hardware, o cálculo de um ou outro será mais rápido. Placas de vídeo geralmente operam com floats, as mais novas, com doubles.

## 1.A

Só explicações sobre o professor

# Aula 02 - Apresentação do Conteúdo

## 2.A
[Sumário](./sumario-links.md)

# Aula 03 - Instalação de Ferramentas

## 3.A
[Links](./sumario-links.md)

# Aula 04 - A Linguagem em Java

## 4.A

ByteCode: 
- Código intermediario 
- É um código que é gerado após o projeto ser compilado
- Ele é executado por uma JVM(JRE)

## 4.B

Apresentando o NetBeans

## 4.C

Gerenciadores de dependência
- Maven
- Grandle
- Ant

Metodo [``main``](./imagens/metodo-main.png):

Ponto de partida de execução do algoritmo, equivalente ao ``inicio`` e ``fim`` do **Portugol**

- ``System.out.println();`` = ``Escreval()`` do Portugol

[First-code](./imagens/first-code.png)

## 4.D

Comentários em JAVA

- ``// Comentário de linha``
- ``/* Comentário de bloco */``
- ``/** Comentário de documentação */``

## 4.E

Comandos de leitura e gravação

O ``Java`` não possui um _leitor / comando de entrada e saída_, então sabendo disso, há a possibilidade de adicionar o ``Scanner``, que é um recurso externo

- ``import java.util.Scanner;`` = Leitor / Comando de entrada e saida do JAVA
- ``Scanner leitor = new Scanner(System.in);`` = Forma de criar um leitor para dentro do **JAVA**
- ``var nome = leitor.nextVar();`` = ``Leia`` do Portugol
  - Forma de ler o próximo dado que se encaixaria naquela variavel
- Tipos de ``Var``
  - `int` 
    - Variavel de número INTEIRO
  - ``float`` e ``double`` 
    - Variaveis de número REAL
    - Diferença:
      - O double tem mais precisão: pode representar mais casas decimais ou números inteiros maiores;
      - O double ocupa 32 bits a mais que o float (o dobro do espaço);
      - Dependendo do hardware, o cálculo de um ou outro será mais rápido. Placas de vídeo geralmente operam com floats, as mais novas, com doubles.

Exemplo de uso dos comandos de _entrada_ e _saída_ // ``Leia`` e ``Escreval``

[Exemplo-1](./imagens/aula4-ex1.png)