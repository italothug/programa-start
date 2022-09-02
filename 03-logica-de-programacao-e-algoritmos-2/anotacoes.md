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

## Comandos

``CREATE TABLE`` + NOME (Nome no plural) : Serve pra criar uma tabela

``DROP TABLE`` + NOME : Serve pra deletar uma tabela

``ID`` : É um ID pra cada registro na tabela

``INT`` : Inteiro ( Usado junto ao ID )

``PRIMARY KEY`` : Chave única ( Usado pra indicar que o ID é único)

``AUTO-INCREMENT`` : Garante que você nunca vai precisar criar um ID / Vai se auto receber um valor

``VARCHAR`` : Mesma função de ``caractere`` e usasse ``(Algum número aqui)`` pra dizer que tem um máximo de letras que podem ser escritas

``NOT NULL`` : Obrigatório informar o nome

``BIT`` : Parecido com o operador lógico, onde recebe a resposta de SIM ou NÃO

``NVARCHAR`` : Tem a mesma função do ``VARCHAR``, só q aceita caracteres extras, como alfabeto arabico, russo, entre outros, que possuem simbolos

``WHERE`` : É obrigatório no código, ele serve pra especificar em qual dos ``ID's`` você quer editar o valor, se não tiver o ``WHERE`` no código, mudará o valor de todos os registros

``CHAR`` : É usado quando você quer um número exato de letras naquela variavel, um bom exemplo é o CPF

``DATE`` : Registrar data sem ocupar muitos espaços da memória

``DATETIME`` : Mesma função de date, porém vc registra a hora tbm

``FLOAT`` : Número com virgula, números reais

``REAL`` : Número com virgula, números reais

_Diferença entre ``FLOAT`` e ``REAL`` é que o **REAL** é mais completo pra grande escala, **FLOAT** é mais simples_

## 3.A

Banco de dados: qualquer repositório que você guarda informações

Comando para criar tabela é:

``CREATE TABLE`` + NOME (Nome no plural) : Serve pra criar uma tabela

``DROP TABLE`` + NOME : Serve pra deletar uma tabela

``ID`` : É um ID pra cada registro na tabela

``INT`` : Inteiro ( Usado junto ao ID )

``PRIMARY KEY`` : Chave única ( Usado pra indicar que o ID é único)

``AUTO-INCREMENT`` : Garante que você nunca vai precisar criar um ID / Vai se auto receber um valor

``VARCHAR`` : Mesma função de ``caractere`` e usasse ``(Algum número aqui)`` pra dizer que tem um máximo de letras que podem ser escritas

``NOT NULL`` : Obrigatório informar o valor da variavel

[Exemplo](./imagens/ex-bda.png)

## 3.B

Inserindo registro no banco de dados

``NVARCHAR`` : Tem a mesma função do ``VARCHAR``, só q aceita caracteres extras, como alfabeto arabico, russo, entre outros, que possuem simbolos

Forma correta de registrar uma pessoa no banco de dados

[Exemplo](./imagens/ex-bda-2.png)

É obrigatório colocar entre aspas simples `'Exemplo'` para o banco de dados reconhecer que isso é um `caractere`, se colocar fora disso, ele reconhece como `número` 

## 3.C

Forma certa de editar registro no banco de dados

[Exemplo](./imagens/ex-bda-3.png)

===================================================

``UPDATE CLIENTES SET NOME = 'Italo C Lima', CPF = '70070070090'``

``WHERE ID = 1``

**Tradução**: ``UPDATE`` _(Nome da tabela)_ ``SET`` _(Nome da coluna)_ ``=`` _('Item da coluna que vai ser modificado')_ ``WHERE ID =`` _(ID da linha que vai ser modificado)_

===================================================

``WHERE`` : É obrigatório no código, ele serve pra especificar em qual dos ``ID's`` você quer editar o valor, se não tiver o ``WHERE`` no código, mudará o valor de todos os registros

Forma certa de excluir registro do banco de dados

``DELETE FROM CLIENTES WHERE ID = 2``

``WHERE`` Sendo obrigatório novamente, para não apagar todos os registros existentes no sistema

## 3.D

Forma de apagar/excluir tabela do banco de dados por código/comando

``DROP TABLE NOMETABELA``

``CHAR`` : É usado quando você quer um número exato de letras naquela variavel, um bom exemplo é o CPF

``DATE`` : Registrar data sem ocupar muitos espaços da memória

``DATETIME`` : Mesma função de date, porém vc registra a hora tbm

``BIT`` : Parecido com o operador lógico, onde recebe a resposta de SIM ou NÃO

## 3.E
Forma de fazer multiplas tabelas e fazer integração/ligação entre si

``FLOAT`` : Número com virgula, números reais

``REAL`` : Número com virgula, números reais

_Diferença entre ``FLOAT`` e ``REAL`` é que o **REAL** é mais completo pra grande escala, **FLOAT** é mais simples_

``FOREIGN KEY`` : Chave estrangeira, ela vai ligar uma tabela á outra, especificando em qual tabela deve ir o valor

- Passo a passo da integração
  - [Passo-1](./imagens/passo1.png) - Primeiro, você faz a tabela que vai ser integrada á outra
  - [Passo-2](./imagens/passo2.png) - Segundo, você faz a tabela que vai integrar, vai receber a integração, vai acontecer tudo nela
  - [Passo-3](./imagens/passo3.png) - Terceiro, você vai dar o valor para a primeira tabela
  - [Passo-4](./imagens/passo4.png) - Quarto, você vai dar os valores da segunda tabela e integrar a categoria no produto

## 3.F

Relacionamentos entre tabelas

- [Passo-1](./imagens/passo1-2.png) // Criando tabela de informação sobre a venda

- [Passo-2](./imagens/passo2-2.png) // Criando tabela de informações contidas na venda

Se colocar ``PRIMARY KEY`` logo no começo, o ``IDVENDA`` ou ``IDPRODUTOS`` só vai poder repetir uma vez e esse não é o intuito

``VALORPRODUTO`` na tabela ``ITENS_VENDAS`` vai servir pra quando tiver promoção, tiver comissão, com isso valor vai poder ser ajustado

- [Passo-3](./imagens/passo3-2.png) // Inserindo produto no estoque

- [Passo-4](./imagens/passo4-2.png) // Registrando a venda do produto

- [Passo-5](./imagens/passo5-2.png) // Registrando informações da venda 

- [Passo-6](./imagens/passo6-2.png) // Registrando informações da venda 2

## 3.G

Forma de fazer pesquisa no banco de dados

- **Exemplo 1**: Quero mostrar ID, PRECO, DESCRIÇÃO da tabela PRODUTOS

===================================================

``SELECT ID, PRECO, DESCRICAO FROM PRODUTOS``

**Tradução**: ``SELECT`` _(Colunas á serem pesquisadas)_ ``FROM`` _(Tabela pra ser pesquisada)_

**Tradução simplificada:** _Selecionar(**SELECT**) os itens da(**FROM**) tabela_ ``produtos``

===================================================

- **Exemplo 2**: Quero mostrar todas as colunas da tabela PRODUTOS

===================================================

``SELECT * FROM PRODUTOS``

**Tradução**: ``SELECT * FROM`` _(Tabela pra ser pesquisada)_

**Tradução simplificada:** _Selecionar(**SELECT**) todos(__*__) os itens da(**FROM**) tabela_ ``produtos``

===================================================

- **Exemplo 3**: Quero mostrar todas as colunas da tabela _PRODUTOS_ mas não quero mostrar o _ID_ da _CATEDORIAID_, quero mostrar o nome registrado na tabela _CATEGORIA_

===================================================

``SELECT P.ID, P.DESCRICAO, P.PRECO, P.QTDESTOQUE, C.NOME``

``FROM PRODUTOS P INNER JOIN CATEGORIAS C``

``ON C.ID = P.CATEGORIAID`` : O que linka é q a tabela _CATEGORIAS_ tem uma coluna **ID** e a tabela _PRODUTOS_ tem uma coluna **CATEGORIA** que chama o **ID** da tabela _CATEGORIAS_

**Tradução**: ``SELECT`` _(Itens com a inicial do nome da tabela)_ ``FROM`` _(Nome da tabela + Inicial)_ ``INNER JOIN`` _(Nome da tabela que tem integração + Inicial)_ ``ON`` _(Inicial + Nome da coluna que está linkada diretamente á coluna da tabela principal)_ ``=`` _(Inicial + nome da coluna principal que recebeu o valor da outra tabela)_

**Tradução simplificada:** _Selecionar(**SELECT**) os seguintes itens da(**FROM**) tabela_ ``PRODUTOS`` _que possui ligação(**INNER JOIN**) com a tabela_ ``CATEGORIAS``, _a ligação(**ON**) acontece entre o ``ID`` de **categorias** e o ``CATEGORIAID`` de **produtos**_

===================================================

- **Exemplo 4**: Mudar o nome da coluna da tabela

===================================================

``SELECT P.ID, P.DESCRICAO, P.PRECO, P.QTDESTOQUE, C.NOME 'CATEGORIA'`` : A coluna **NOME** será trocada por **CATEGORIA**

===================================================

- **Exemplo 5**: Colocar um filtro pra mostrar umas tabelas especificas, Como _**preço < 10**_

===================================================

``WHERE P.PRECO < 10``

``WHERE P.PRECO < 10 OR P.QTDESTOQUE > 10``

``WHERE P.PRECO < 10 AND P.QTDESTOQUE > 10``

_Observação: Para ser aplicada, é necessário colocar isso após o **Exemplo 3**_

===================================================

São exemplos de filtros

## 3.H

Mostrando o valor total

===================================================

**Exemplo 1**: Exemplo de caso vendesse tudo do estoque, qual seria o retorno?

``SELECT P.ID 'CÓDIGO', P.DESCRICAO, (P.PRECO * P.QTDESTOQUE) 'TOTAL', C.NOME ``

``FROM PRODUTOS P INNER JOIN CATEGORIAS C``

``ON P.CATEGORIAID = C.ID``

**Tradução**: _**Selecionar**``(SELECT)`` o **ID de produtos**``(P.ID)`` depois troque o nome pra **código**``('CÓDIGO')``, selecionar **descrição de produtos**``(P.DESCRICAO)``, fazer a **soma total entre preço e estoque**``(P.PRECO * P.QTDESTOQUE)`` pra saber o total que seria vendido, **depois troque o nome dessa soma pra total**``('TOTAL')``, depois selecione o **item nome na tabela categorias**``(C.NOME)``. Todas essas seleções **serão da**``(FROM)`` **tabela produtos, inicial P**``(PRODUTOS P)``, e com **ligação**``(INNER JOIN)`` á tabela **categorias, inicial C**``(CATEGORIAS C)``, essas duas **possuem ligações**``(ON)`` entre o item **CATEGORIAID da tabela produtos**``(P.CATEGORIAID)`` e o **ID da tabela categorias**``(C.ID)``_

===================================================

**Exemplo 2**: Quero saber o valor final que foi vendido os últimos produtos

``SELECT IDPRODUTO, (VALORPRODUTO - (VALORPRODUTO * DESCONTO / 100)) FROM ITENS_VENDAS``

===================================================

``COUNT`` : _Faz a contagem de registros e com ele, você pode fazer um agrupamento_

**Exemplo 3**: Somar os itens que possuem aquela categoria e mostrar quantos tem em cada item

``SELECT COUNT(P.ID), C.NOME FROM PRODUTOS P INNER JOIN CATEGORIAS C``

``ON P.CATEGORIAID = C.ID``

``GROUP BY P.CATEGORIAID``

_Obs: JUNTANDO TODOS OS ITENS QUE POSSUEM O MESMO CATEGORIAID_

===================================================

**Exemplo 4**: Organizar a tabela de acordo com uma coluna especifica

`SELECT * FROM PRODUTOS ORDER BY DESCRICAO`

_Obs: Se adicionar_ ``DESC`` _no final, invés de ficar na ordem crescente, fica na ordem decrescente_

`SELECT * FROM PRODUTOS ORDER BY DESCRICAO DESC`

===================================================

# Aula 04 - Orientação Objetos

## 4.A

Exemplo 1: Criar uma variavel que dê para armazenar 3 tipos de dados diferentes, como nome, cpf e idade.

[Exemplo1](./imagens/aula4-ex1.png)