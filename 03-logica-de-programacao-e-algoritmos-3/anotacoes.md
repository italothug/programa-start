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

Exercicio com estutura de repetição 2

Exercicio 22

## 4.P

Exercicio 22 (Continuação)

## 4.Q

Programação orientada á objetos
- Pegar um problema, passar a realidade do mundo para o sistema
- Envolve 4 principios básico
  - Polimorfismo
  - Herança
  - Abstração
    - Fazer o reconhecimento do que é importante no mundo real e trazer para dentro do algoritmo
  - Encapsulamento
    - É uma forma de segurança, que funciona parecido com uma pessoa, que ela sabe das suas próprias informações

## 4.R

Conceito de classe
- Ela é uma forma do meu objeto
- A classe descreve uma entidade, ex: Pessoa

## 4.S

`Public` : Procedimentos e Funções do Visualg

## 4.T

Continuação de procedimentos e funções

**Classe main** é o código onde fica os _códigos principais_ e a **classe pessoa** é onde fica os _procedimentos_ que serão implementados na classe main

[Main](./imagens/procedimento-funcao-main.png)

[Pessoa](./imagens/procedimento-funcao-pessoa.png)

## 4.U

Modificadores de acesso / Procedimento

Nos métodos anteriores, criamos formas erradas de mandar valores para classe pessoa, nesse novo método, iremos aprender a forma certa

Isso vai fazer com que a classe se torne mais privada e com dificil acesso

[Main](./imagens/procedimento-funcao-main-private.png)

[Pessoa](./imagens/procedimento-funcao-pessoa-private.png)

## 4.V

Metódos construtores
- Vai servir para levar um valor padrão de uma classe á outra

Exemplo: Da classe [Pessoa](./imagens/metodo-construtor-pessoa.png) para a classe [Main](./imagens/metodo-construtor-main.png)

## 4.W

Herança no Java

_Observação: O Date é uma variavel que não é nativa do Java, então é necessário importar, e o próprio Apache faz isso automatico, segue o exemplo:_ [Etapa1](./imagens/import-auto1.png) [Etapa2](./imagens/import-auto2.png)


Forma rápida de escrever todos os metódos acessores (Get e Set):
- Alt + Insert em alguma parte do código
- Vá na opção "Getter and Setter"
- Marca todas a opções e clica em "Generate"

[Print1](./imagens/get-e-set-p1.png)

[Print2](./imagens/get-e-set-p2.png)

## 4.X

Metódo certo de usar Herança no Java
- Forma de identificar herança, é sabendo o tipo da classe, ex: Vendedor ( é um tipo de Funcionário )
- Usando o `extends + classe`, por ex: `Vendedor extends Funcionario`, o vendedor irá ter tudo q o funcionário tem. [PRINT](./imagens/heranca-extends.png)

## 4.Y

Continuando o metódo herança no Java
- Quando estou na classe Vendedor e quero pegar um comando da classe Funcionário, é necessário usar o comando `super()`
  - Motivo: Pq quando você está na classe Vendedor e a mesma está extendida para classe Funcionário, é como se você estivesse em baixo e o Funcionário estivesse em cima, então para vc acessar a parte de cima, vc usa o `super()`
  
  [Exemplo](./imagens/metodo-heranca-super.png)
- `This` é usado para pegar metodos da mesma classe

# Aula 05 - Exercícios Lógicos
## 5.A
Exercicio
20. A concessionária de veículos “CARANGO VELHO” está vendendo os seus veículos com desconto. Faça
um algoritmo que calcule e exiba o valor do desconto e o valor a ser pago pelo cliente de vários carros. O
desconto deverá ser calculado de acordo com o ano do veículo. Até 2000 - 12% e acima de 2000 - 7%. O
sistema deverá perguntar se deseja continuar calculando desconto até que a resposta seja: “(N) Não”.
Informar total de carros com ano até 2000 e total geral;

[Como fiz](./imagens/exercicio-20-eu.png)

Professor fez [Parte 1](./imagens/exercicio-20-certo-1.png) / [Parte 2](./imagens/exercicio-20-certo-2.png)

## 5.B
Exercicio 20 (Continuação)

# Aula 06 - Exercícios POO