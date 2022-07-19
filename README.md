# dio-desafio-unimed-iniciais-js-2022
Desafios Iniciais em Javascript (3 Desafios)

## Desafios Básicos em JS

### Desafio 01 (DDD)
Leia um número inteiro que representa um código de DDD para discagem interurbana. Em seguida, informe à qual cidade o DDD pertence, considerando a tabela abaixo:

![Tabela DDD](https://resources.urionlinejudge.com.br/gallery/images/problems/UOJ_1050.png)

Se a entrada for qualquer outro DDD que não esteja presente na tabela acima, o programa deverá informar:
DDD nao cadastrado

**Entrada**
A entrada consiste de um único valor inteiro.

**Saída**
Imprima o nome da cidade correspondente ao DDD existente na entrada. Imprima DDD nao cadastrado caso não existir DDD correspondente ao número digitado.
 
Exemplo de Entrada	Exemplo de Saída
11  Sao Paulo


### Desafio 02 (Animal)
Neste problema, você deverá ler 3 palavras que definem o tipo de animal possível segundo o esquema abaixo, da esquerda para a direita. Em seguida conclua qual dos animais seguintes foi escolhido, através das três palavras fornecidas.

![Tabela Animais](https://resources.urionlinejudge.com.br/gallery/images/problems/UOJ_1049_b.png)

Entrada
A entrada contém 3 palavras, uma em cada linha, necessárias para identificar o animal segundo a figura acima, com todas as letras minúsculas.

Saída
Imprima o nome do animal correspondente à entrada fornecida.

 
Exemplos de Entrada	Exemplos de Saída
vertebrado  homem
mamifero
onivoro

vertebrado  aguia
ave
carnivoro

invertebrado  minhoca
anelideo
onivoro


### Desafio 03 (Andando no Tempo)
Imagine o seguinte cenário, você desenvolveu uma máquina de  teletransporte no tempo que pode ser usada no máximo três vezes, e a cada uso da máquina você pode escolher ir para o futuro ou voltar para o passado. A máquina possui três créditos fixos; cada crédito representa uma certa quantidade de anos, e pode ser usado para ir essa quantidade de anos para o passado ou para o futuro. Você pode fazer uma, duas ou três viagens, e cada um desses três créditos pode ser usado uma vez apenas. Por exemplo, se os créditos forem 5, 12 e 9, você poderia decidir fazer duas viagens: ir 5 anos para o futuro e, depois, voltar 9 anos para o passado. Dessa forma, você terminaria quatro anos no passado, em 2012. Também poderia fazer três viagens, todas indo para o futuro, usando os créditos em qualquer ordem, terminando em 2042.

Neste desafio, dados os valores dos três créditos da máquina, seu programa deve dizer se é ou não possível viajar no tempo e voltar para o presente, fazendo pelo menos uma viagem e, no máximo, três viagens; sempre usando cada um dos três créditos no máximo uma vez.

Entrada
A entrada consiste de uma linha contendo os valores dos três créditos A, B e C (1 ≤ A, B, C ≤ 1000).

Saída
Seu programa deve imprimir uma linha contendo o caracter “S” se é poss ível viajar e voltar para o presente, ou “N” caso contrário.
 
Exemplos de Entrada	Exemplos de Saída
22 5 22 S

31 110 79 S

45 8 7  N
