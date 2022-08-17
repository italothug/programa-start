# Aula 01 - Introdução

## 1.A

Explicações básicas

## 1.B

Algoritmo é um passo a passo pra obter seu produto final

IDE é uma ferramenta de desenvolvimento para escrever seu código

Programação de Alto Nivel e Baixo Nivel

- **Alto Nivel** = Você não se preocupa com hardware

- **Baixo Nivel** = Você se preocupa com seu hardware

## 1.C

Linguagem de programação e suas funcionalidades

**PHP**: Para desenvolvimento de WEB

**JAVA**: Para todos os tipos de aparelhos, sistemas e qualquer area 

**C#**: Mesma ideia do JAVA, porém é focado na plataforma Windows e é um pouco mais fácil

**COBOL**: Linguagem feita para aplicações comerciais, grande parte dos bancos ainda usam ela

**C e C++**: Linguagem que foi utilizada para criar o Windows

## 1.D

``Escreval("")`` É algo que você quer que seja escrito na tela de console

## 1.E

Para somar 2 números é necessário declarar variáveis que suporteem números, +, -, / e assim vai

Se você quer combinar variáveis, você precisa declarar essas variáveis como literais, tipo nomes, cep's, número da casa

Você pode declarar 1 variável por linha ou todas as variáveis na mesma linha;

Exemplo1:

  ``nome: caractere``

  ``sobrenome: caractere``

  ``nomeCompleto: caractere``

Exemplo2:

  ``nome, sobrenmome, nomeCompleto: caractere``

# Aula 02 - Trabalhando com Tipos

## 2.A

### Linguagens Fortemente tipadas x Fracamente tipadas

**Linguagem Fortemente Tipada** 

_É uma linguagem onde o dado conhecido como inteiro só vai aceitar número inteiro, tipo de dado real só vai aceitar número inteiro ou número com virgula, tipo de dado caractere vai aceitar qualquer tipo de palavra_

[PRINT](./imagens/Screenshot_88.png)

## 2.B

Exemplo:

[PRINT](./imagens/Screenshot_89.png)

Operador ``lógico`` é pra ver se aquilo é verdade ou mentira

[LOGICO](./imagens/Screenshot_90.png)

## 2.C

Metódo certo de usar o ``se``

Exemplo:

[PRINT](./imagens/Screenshot_91.png)

## 2.D

Complemento do uso do ``se``

Exemplo:

[PRINT](./imagens/Screenshot_92.png)

## 2.E

Complemento do ``se``

_Obs: pra cada ``se`` no código, deve ser colocado um ``fimse`` no final. Ex: 3 ``se`` no código = 3 ``fimse`` no final_

[PRINT](./imagens/complemento-do-se.png)

## 2.F

### Tabela verdade

Formas de usar o ``E``, ``&&``

[PRINT](./imagens/forma-uso-e.png)

Formas de usar o ``OU``, ``or``, ``||``

[PRINT](./imagens/uso-ou.png)

## 2.G

Verificando se é um triângulo ou não (Exercicio de empresas)

[PRINT](./imagens/exercicio-triangulo.png)

## 2.H

### Operadores extras e conceito de curto circuito

Operadores extras

[Print](./imagens/operadores-extras.png)

**Conceito de curto circuito**

_É pelo o fato de o programa ler blocos em sequências, no exemplo a seguir, veremos um bloco vermelho, um azul e um verde. Então para poupar tempo e ter maior **desempenho**, se o primeiro bloco for verdade e o programa ver que está apto a passar para próxima fase, então não ira ler os blocos seguintes._

[Print](./imagens/curto-circuito.png)

## 2.I

### Operador de multipla escolha

_Não é obrigatório usa-lo, ele pode ser trocado por ``se`` e ``senao``_

Alternativa da multipla usando o ``se``

[Print](./imagens/alternativa_para_se.png)

Usando o operador de multipla escolha, ele só trabalha exclusivamente com igualdade

[Print](./imagens/usando-o-escolha.png)

## 2.J

### MOD e DIV

- DIV

Retorna o número inteiro em uma divisão, mesmo sendo um número quebrado, retornará apenas o número inteiro e não retornará os números depois da virgula

[Exemplo](./imagens/DIV.png)

- MOD ou %

Retorna o resto da divisão, como se 10 / 3, o número mais próximo de dividir isso seria 9 e **iria sobrar o 1**

[Exemplo](./imagens/MOD.png)

A forma de uso seria pra saber se o número dito pelo o usuario é impar ou par

[Exemplo](./imagens/par.png)

Outra forma de uso é pra saber se o número dito pelo o úsuario é multiplo de algum número

# Aula 03 - Operadores e Exercícios

## 3.A

### Operador "enquanto"

``Enquanto = while``

O ``enquanto`` irá rodar como um looping até oq está escrito nele ser atingido 

[Exemplo](./imagens/ex5.png)

## 3.B

### Operador "enquanto"

Usando o ``se`` e ``interrompa`` dentro do ``enquanto`` para parar a contagem

[Exemplo](./imagens/interrompa.png)

## 3.C

### Exercitando o "enquanto"

- O IBGE tá fazendo uma pesquisa de idade das pessoas e no final vai querer saber: pessoa mais nova, mais velha, % de menores de idade e a média das idades

[Variaveis](./imagens/declaracao-e-qtd-inicial.png) declaradas

[Resolução](./imagens/resolucao-e-cmd.png) da questão + comentado e explicado

## 3.D

### Operador "repita"

A diferença do ``repita`` para o ``enquanto``, é que ele roda pelo menos 1 vez o seu código antes de repetir e fazer alguma alteração

Outra forma de escrever o ``repita`` em outras linguagens é

"``do``

``while``"

[Exemplo](./imagens/ex-repita.png)

Criar uma senha e ter acertar ela em dentro de 5 tentativas

[Senha](./imagens/ex-senha.png)

## 3.E

Criando menu para pagar conta da manutenção do veiculo

[Exemplo](./imagens/conta.png)

## 3.F

### Operador "para"

Melhor amigo de vetores

O operador ``para`` faz com que a variavel vá de um número ao outro de forma mais simples, podendo colocar condições

[Exemplo](./imagens/ex-para.png)

## 3.G

### Complemento "passo" no operador "para"

O complemento ``passo`` funciona como uma forma do uso do ``MOD``, porém ele é mais simples

[Exemplo](./imagens/ex-passo.png)

Nele pode ser usado o:
- 2 -> que irá pular o número de 2 em 2
- 3 -> que irá pular o número de 3 em 3
- -1 -> que invertendo os números do complemento ``para`` você consegue colocar invertido, EX:
  - Normal: ``para i de 10 ate 100 passo 5 faca``
  - Invertido: ``para i de 100 ate 10 passo -5 faca``

Também é possivel declarar variáveis com os valores e colocar no Operador ``para``

[Exemplo](./imagens/ex-passo-2.png)

## 3.H

### Função "aleatorio"

Uma função que você pode sortear um número

[Exemplo](./imagens/ex-aleatorio.png)

## 3.I

