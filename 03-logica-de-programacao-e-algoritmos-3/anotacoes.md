# Aula 01 - Boas Vindas

## Comandos
- Operadores
  - `+ adição`
  - `- subtração`
  - `* multiplicação`
  - `/ divisão`
  - `% resto da divisão`
- Operadores relacionais
  - `> : Maior que`
  - `< : Menor que`
  - `>= : Maior ou igual á`
  - `<= : Menor ou igual á`
  - `== : Igual á`
  - `!= : Diferente de`
- Operadores lógicos
  - `&&` : É o mesmo que o `E/AND` do Portugol/Visualg
  - `||` : É o mesmo que o `OU/OR` do Portugol/Visualg
  - `!` : Negação / Não quero q uma coisa seja verdade
- ``System.out.println();`` = ``Escreval()`` do Portugol
- ``// Comentário de linha``
- ``/* Comentário de bloco */``
- ``/** Comentário de documentação */``
  - É um comentário que sai expresso em um papel, comentário usado muitas vezes em empresas com outras pessoas que precisam ler seu código.
- ``import java.util.Scanner;`` 
  - Leitor / Comando de entrada e saida do **JAVA**
- ``Scanner leitor = new Scanner(System.in);``
  - Forma de criar um leitor para dentro do **JAVA**
- ``nome da variavel = leitor.nextVar();`` = ``Leia`` do Portugol
  - Forma de ler o próximo dado que se encaixaria naquela variavel
- Tipos de ``Variaveis`` primitivas
  - `int` : 
    - número inteiro
  - `float` : 
    - número real, ex: 5.0f (O **f** é obrigatório para dizer que a variavel tem o tipo `float`)
  - `double` : 
    - número com virgula (Um pouco mais pesado que o float), ex: 4.0d (O **d** é obrigatório para dizer que a variavel tem o tipo `double`)
  - `char` : 
    - armazena uma única letra, como por ex: Masculino(**M**) Feminino(**F**)
  - `byte` : 
    - armazena número inteiro de 8-bit, de 0 a 255
  - `boolean` : 
    - armazena valores lógicos, como verdadeiro(**true**) ou falso(**false**)
- Tipos de `Variaveis` não primitivas
  - `String` : 
    - armazena textos, ex: `String nome = "Essa é uma variável do tipo String";`
- `if( ){ }` : _( Aula 4.H )_
    - Se + condição + o que fazer, [Exemplo2](./imagens/aula4-ex2.png)
- `else` : 
     - É o mesmo que o `Senao` do Portugol
- `Switch` : (Aula 4.I)
  - Escolha do Visualg
- `Case 1` : 
  - Caso 1
- `Break` : 
  - Interrompa
- `Default` : 
  - Outrocaso
- `For` _( Aula 4.L )_
  - **Para** do Visualg

- `While` 
  - **Enquanto** do Visualg

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

## 4.F

Variaveis, tipos e operadores

- Variaveis
  - Para criar uma variavel é necessário o _( tipo da variavel, nome e o ponto e virgula )_, ex: ``int idade;``
  - Também é possivel adicionar o valor na mesma linha da variavel, só colocar o _( = valor )_, ex: ``int idade = 20;``

- Tipos primitivos de variaveis
  - `int` : 
    - número inteiro
  - `float` : 
    - número real, ex: 5.0f (O **f** é obrigatório para dizer que a variavel tem o tipo `float`)
  - `double` : 
    - número com virgula (Um pouco mais pesado que o float), ex: 4.0d (O **d** é obrigatório para dizer que a variavel tem o tipo `double`)
  - `char` : 
    - armazena uma única letra, como por ex: Masculino(**M**) Feminino(**F**)
  - `byte` : 
    - armazena número inteiro de 8-bit, de 0 a 255
  - `boolean` : 
    - armazena valores lógicos, como verdadeiro(**true**) ou falso(**false**)

- Tipos não primitivos de variaveis
  - `String` : 
    - armazena textos, como se fosse o `Escreval` do Portugol, ex: `String nome = "Essa é uma variável do tipo String";`

- Operadores
  - `+ adição`
  - `- subtração`
  - `* multiplicação`
  - `/ divisão`
  - `% resto da divisão`

## 4.G
- Estruturas condicionais
  - `if` : 
    - É o `Se` do Portugol
  - `switch` : 
    - É o `Escolha caso` do Portugol

## 4.H
- Estrutura condicional
  - `if( ){ }` : 
    - Se + condição + o que fazer, [Exemplo2](./imagens/aula4-ex2.png)
  - `else` : 
     - É o mesmo que o `Senao` do Portugol

- Operadores relacionais
  - `> : Maior que`
  - `< : Menor que`
  - `>= : Maior ou igual á`
  - `<= : Menor ou igual á`
  - `== : Igual á`
  - `!= : Diferente de`
  
- Operadores lógicos
  - `&&` : É o mesmo que o `E/AND` do Portugol/Visualg
  - `||` : É o mesmo que o `OU/OR` do Portugol/Visualg
  - `!` : Negação / Não quero q uma coisa seja verdade

## 4.I

Segunda estrutura condicional

- `Switch` : Escolha do Visualg
- `Case 1` : Caso 1
- `Break` : Interrompa
- `Default` : Outrocaso

[Metodo](./imagens/metodo-escolha-switch.png)

## 4.J

Exercicios ..

## 4.K

Inicio da estrutura de repetição

Para = For

Enquanto = While

## 4.L

Estrutura de repetição `For / Para`
  - É uma estrutura de repetição
  - Ela é aplicada na circunstância que você sabe quantas vezes aquilo deve ser repetido
  - A variavel pode ser criada dentro da estrutura

- `for(int i = 0; i <= 10; i++/i = i + 1){}`
    - tradução: `for`(variavel de controle/criação da variavel; condição de parada; incremento/aumento da variavel )

## 4.M

Estrutura de repetição `While / Enquanto`
- A parada da repetição depende de que algo aconteça 

Exemplo aplicando `while`: [Exemplo](./imagens/estrutura-while.png)

## 4.N

Exercicio com estrutura de repetição

Exercicio 24

## 4.O

