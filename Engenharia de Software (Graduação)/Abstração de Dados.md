___
Disciplina.: [[Arquitetura de Computadores]]
___
## <mark style="background: #FFF3A3A6;">Aula</mark>

**Estruturas de dados básicas**

Sabemos que as informações no computador estão armazenadas em células de memória com endereços específicos e muitos detalhes relacionados. Estruturas de dados são formas do cliente (programador, usuário, outro sistema) atuar com o sistema sem ficar preso aos detalhes do armazenamento da informação na memória do computador. Chamamos isso de “abstração de dados” que ganham forma nas estruturas de dados que são decisivas para que o programador expresse os algoritmos de forma mais eficiente.

**Vetor (array ou Listas contígua)**

Uma lista é uma coleção de elementos que aparecem sequencialmente. São exemplos: listas de convidados para uma festa, lista de compras. Nomes também podem ser vistos como listas de letras. Pode-se abstrair uma lista:

Um vetor ou _array_ permite acesso direto a qualquer elemento da lista, isto é, você não precisa percorrer todos os elementos de uma lista até encontrar o que você precisa, basta usar o índice da estrutura. Observe a figura abaixo uma parte da memória do computador, as informações estão uma “ao lado” da outra.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939326918-SWBlBvU0zv.png)

Abaixo temos uma representação semelhante.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939344811-DfGKdCH9HW.png)

Considere que a lista se chame LEITURAS.

LEITURAS [1] indica o conteúdo na posição 1, LEITURAS [2], a posição 2 e assim por diante.

Essa forma de estrutura de dados em vetor permite acesso direto a uma determinada posição do vetor.

Considere abaixo a posição 5 (índice 5), onde temos o elemento 2.5.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939364311-wOX5es9KFN.png)

A inserção de um novo elemento irá forçar que os demais elementos sejam deslocados pela estrutura exigindo um laço de programação.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939385686-xOtjPB9lU1.png)

Em outras palavras, a inserção de um elemento no vetor sem copiar por cima de um elemento pré-existente requer movimentar os elementos restantes da lista. Decididamente incluir um elemento em um vetor sem apagar o anterior tem certo custo de programação! Isso é diferente da estrutura lista ligada que veremos mais adiante.

**1.2 - Matrizes**

Matrizes são estruturas importantes e comuns e consistem de vetores bidimensionais. Considere os dados como se estivesse todos dispostos em uma tabela, isto é, uma estrutura retangular contendo elementos de um mesmo tipo (no caso de matriz homogênea). Pense em uma forma de representar a ocupação de lugares em um teatro. A cada venda de um bilhete é preciso armazenar a informação evitando que duas pessoas tenham o mesmo número de assentos. Observe a praticidade de se marcar assento ocupado. Imagine que uma pessoa tenha reservado o assento 7 na 4ª. fileira.

Simplificando bastante o processo, considerando uma estrutura de dados chamada LUGARES contendo a representação de todos os assentos do teatro contendo 20 fileiras de bancos e 15 assentos em cada fileira, temos a representação abaixo:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939410236-bH6sDUyC04.png)

Marcar o assento do assento 7 da 4ª. fileira poderia ser algo assim:

LUGARES [4][7] = 1; /* repare que a posição da poltrona linha 4, coluna 7 foi marcada */

**1.3 – Listas ligadas**

Se o armazenamento dos elementos da lista anterior estiver em blocos de letras espalhados pela memória e não “colados uns aos outros”, temos uma **lista ligada**.

Uma lista ligada tem importante diferença com relação a vetores porque geralmente será utilizada quando o tamanho da memória do computador a ser alocado não é conhecido _a priori_ e mais memória deve ser alocada dinamicamente, isto é, durante a execução do próprio programa.

Cada elemento da lista, neste caso o nome de uma pessoa, precisa ter um endereço apontando para o próximo elemento da lista. A lista ligada precisa de um ponteiro apontando para o início da lista e um ponteiro no final da lista apontando para o seu final.

**Importante perceber as diferenças nos métodos de busca e adição e eliminação de elementos em uma lista ligada. Depende somente da mudança de endereços de apontadores!**

Uma lista ligada não permite acesso direto a qualquer elemento da lista (como em um vetor), isto é, você precisa percorrer todos os elementos de uma lista até encontrar o que você precisa.

Listas ligadas são muito usadas quando não se sabe o tamanho da memória requerida para uma determinada aplicação.

Assim, a lista é preferível ao vetor (lista contígua) quando houver necessidade de inserir e remover elementos. Já em um vetor, é necessário fazer muitos deslocamentos de nomes se for necessário preencher a lista com novos elementos. Mas a vantagem do vetor é o acesso direto, lembre-se!

Repare abaixo a movimentação de ponteiros (dica: havendo ponteiros, é lista ligada, havendo índice, é vetor).

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939447531-eDsgpp2J7E.png)

​Visto de outra forma, a lista tem um início e cada elemento aponta para a localização do elemento seguinte (essa é a ideia do ponteiro representado por uma seta).​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939519531-bMwWIG6wZM.png)

​Quando queremos eliminar um elemento da lista, podemos simplesmente desviar a posição do ponteiro e nenhum elemento aponta para o elemento a ser eliminado. Isso equivale à sua eliminação.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939546572-yS7ZrTWwrs.png)

​A inclusão de um elemento na lista mais uma vez significa ajuste de ponteiros. O novo elemento deve apontar para seu sucessor.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939569700-sKUgPluWs3.png)

**1.4 – Árvore**

Em uma **árvore**, a organização dos elementos se dá de forma hierárquica, existindo um elemento que fica no topo da árvore, chamado de **raiz** e os elementos subordinados a ele, seus nós filhos.

Cada nó filho pode conter zero, um ou mais de um nó filho.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939596012-M4vH4mfUWv.png)

Olhando para uma árvore por camadas:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939623232-MgV4vly7pS.png)

Note que a implementação da árvore se dá por lista ligada mas poderia ser por vetores também. Isto é uma lista ou um vetor pode representar uma árvore, embora a representação por listas seja mais fácil de se encontrar em algoritmos.

O NIL representa um ponteiro que não aponta para outro elemento.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939677253-OfiTR7551p.png)

Uma **árvore binária** é uma estrutura de dados específica, útil quando precisam ser tomadas decisões bidirecionais em cada ponto de um processo. Note que em uma árvore binária, à esquerda de um nó pai, os filhos da subárvore esquerda são menores e os filhos da subárvore direita são maiores.

Um exemplo de aplicação: encontrar todas as repetições em uma lista de números, verificar se um dado elemento está presente na árvore ou não está, qual o menor ou qual o maior elemento de uma lista.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939710751-mq9qdHF9B2.png)

**2 - Outros tipos de estruturas importantes**

**Pilhas**

Quando operamos uma estrutura em que as operações de inserção ou remoção ocorrem só em um dos extremos da lista, chamamos essa estrutura de uma **pilha**.

A consequência dessa restrição é que o último elemento a entrar na estrutura é o primeiro a ser removido, isso leva as pilhas a serem conhecidas como estruturas “last-in, first-out – **LIFO**”. A extremidade em que as operações ocorrem é chamada de topo da pilha, a outra é chamada de base da pilha. O processo de inserir um objeto no topo da pilha é chamado de empilhamento (**push**), o de remover, operação de desempilhamento (**pop**).

Veja na ilustração abaixo como os elementos de uma lista podem ser copiados a fim de formar uma pilha.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939738978-K67dFzmOee.png)

​Uma vez criada a pilha, seus elementos podem ser descarregados mas sempre a partir do topo da pilha, conforme a ilustração a seguir:​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939771053-RaGoHi1UZP.png)

**2.2 - Filas**

Em uma fila, as inserções são realizadas em uma extremidade e as remoções na outra. É o esquema first-in, first-out – **FIFO**. Outra forma de considerar fila é pensar que nela os objetos são retirados de acordo com a ordem com que chegaram. A extremidade na qual são retirados os elementos é chamada de início da fila, onde eles são inseridos é chamado de fim da fila.

Abaixo uma fila em diferentes momentos de processamento:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939799612-EvUl1d5cmP.png)

Outro exemplo da dinâmica de uma fila:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939835334-EvbMiWZzkH.png)

**3 - Um exemplo de aplicação**

Observe como as instruções são executadas, de forma ilustrativa, na memória do computador.

A instrução PUSH deposita um valor no topo da pilha, a instrução POP desempilha um valor do topo da pilha, ADD significa adicionar o topo ao vizinho imediato, de forma análoga MUL é multiplicar e SUB é subtrair.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667939863353-8s8i2JR1U7.png)

Ao término das execuções, o topo da pilha contém somente o número 18.

Referência Bibliográfica

BROOKSHEAR, J.G. **Ciência da Computação: uma visão abrangente.** Porto Alegre: Bookman, 2013.

DROSDEK, A. **Estruturas de Dados e Algoritmos em C++.** São Paulo: CENGAGE, 2018.

FORBELLONE, A.L.V. & EBERSPACHER, H. F.  **Lógica de Programação –  A Construção de Algoritmos e Estruturas de Dados.** 3ª. Edição. São Paulo, SP: Prentice Hall, 2005.
## <mark style="background: #BBFABBA6;">Resumo</mark>

**1. Introdução à Abstração de Dados**

- Abstração de dados permite que programadores trabalhem com estruturas de dados sem se preocupar com os detalhes de implementação na memória do computador.
- Estruturas de dados são formas de organizar e armazenar dados para acesso e manipulação eficientes.

**2. Estruturas de Dados Básicas**

- **Vetor (Array):**
    - Coleção de elementos armazenados sequencialmente na memória.
    - Permite acesso direto a qualquer elemento pelo seu índice.
    - Inserção e remoção de elementos podem ser custosas, pois exigem deslocamento de outros elementos.
- **Matriz:**
    - Estrutura bidimensional (tabela) que armazena elementos do mesmo tipo.
    - Útil para representar dados em formato de grade (ex: assentos em um teatro).
- **Lista Ligada:**
    - Elementos armazenados em diferentes locais da memória, conectados por ponteiros.
    - Flexível para inserção e remoção de elementos, pois só requer ajuste de ponteiros.
    - Não permite acesso direto, exige percorrer a lista para encontrar um elemento.
- **Árvore:**
    - Estrutura hierárquica com um elemento raiz e nós filhos.
    - Implementada com listas ligadas ou vetores.
    - Árvore binária: cada nó tem no máximo dois filhos (esquerda e direita).
    - Útil para busca, ordenação e outras operações.

**3. Outras Estruturas Importantes**

- **Pilha:**
    - Estrutura LIFO (Last-In, First-Out).
    - Operações de inserção (push) e remoção (pop) ocorrem apenas no topo.
    - Exemplo: pilha de pratos.
- **Fila:**
    - Estrutura FIFO (First-In, First-Out).
    - Operações de inserção (enqueue) ocorrem no final e remoção (dequeue) no início.
    - Exemplo: fila de banco.

**4. Exemplo de Aplicação**

- Ilustração de como as instruções `PUSH`, `POP`, `ADD`, `MUL` e `SUB` manipulam uma pilha na memória.
## <mark style="background: #FFB86CA6;">Flash Cards</mark>

#flashcards-ArquiteturaDeComputadores

##### Exercícios da Aula

VERDADEIRO OU FALSO - Em um vetor (array), o tamanho da lista de valores é pré-determinado e um elemento pode ser acessado diretamente::VERDADEIRO

VERDADEIRO OU FALSO - Em uma lista ligada, à lista de valores tem um apontador para o início da lista e um código para determinar o fim da lista::VERDADEIRO

VERDADEIRO OU FALSO - Inserir ou eliminar um elemento em uma lista ligada depende de ajuste de ponteiros e é um processo relativamente simples::VERDADEIRO

VERDADEIRO OU FALSO - Inserir ou eliminar um elemento de um vetor é relativamente trabalhoso e exige movimentação interna dos valores na lista::VERDADEIRO

VERDADEIRO OU FALSO - Uma estrutura em árvore pode ser implementada por meio de vetores ou lista ligada::VERDADEIRO

VERDADEIRO OU FALSO - Em um vetor o acesso é direto a um determinado elemento via índice::VERDADEIRO

VERDADEIRO OU FALSO - Em uma lista ligada o acesso a um determinado elemento é sequencial um a um, a partir do ponteiro do início da lista::VERDADEIRO

VERDADEIRO OU FALSO - Listas ligadas são usadas para alocação dinâmica de memória::VERDADEIRO

VERDADEIRO OU FALSO - Vetores são usados quando se sabe o tamanho de memória necessário::VERDADEIRO
###### GEMINI

O que é abstração de dados?::Permite trabalhar com estruturas de dados sem se preocupar com detalhes de implementação.

O que são estruturas de dados?::Formas de organizar e armazenar dados para acesso e manipulação eficientes.

Quais são as estruturas de dados básicas?::Vetor, matriz, lista ligada e árvore.

O que é um vetor (array)?::Coleção de elementos armazenados sequencialmente na memória, com acesso direto por índice.

Quais as vantagens e desvantagens do vetor?::Vantagem: acesso direto. Desvantagem: inserção e remoção podem ser custosas.

O que é uma matriz?::Estrutura bidimensional que armazena elementos do mesmo tipo, útil para representar dados em formato de grade.

O que é uma lista ligada?::Elementos armazenados em diferentes locais da memória, conectados por ponteiros.

Quais as vantagens e desvantagens da lista ligada?::Vantagem: inserção e remoção eficientes. Desvantagem: sem acesso direto.

O que é uma árvore?::Estrutura hierárquica com um elemento raiz e nós filhos.

O que é uma árvore binária?::Árvore em que cada nó tem no máximo dois filhos.

O que é uma pilha?::Estrutura LIFO (Last-In, First-Out), com operações push e pop no topo.

O que é uma fila?::Estrutura FIFO (First-In, First-Out), com operações enqueue no final e dequeue no início.

Quais as diferenças entre pilha e fila?::Pilha: LIFO, operações no topo. Fila: FIFO, operações no início e no final.

