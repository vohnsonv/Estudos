___
Disciplina.: [[Lógica de Programação]]
___
## <mark style="background: #FFF3A3A6;">Aula</mark>

Bem-vindo ao estudo sobre Vetor! Essa aula te ajudará na compreensão de alguns conceitos que são importantes no contexto de programação. Vamos conhecer melhor esses conceitos?

Estrutura Homogênea Unidimensional é uma estrutura de dados muito simples, também conhecida como vetor ou array. Possui apenas uma dimensão e pode armazenar diversas variáveis do mesmo tipo. Cada item (ou elemento) do vetor pode ser acessado por um índice (RIBEIRO, 2019).

Imagine o seguinte problema: Você precisa criar um algoritmo que lê o nome de uma lista de alunos de uma turma. E se essa turma tem 50 alunos? No problema apresentado, é possível utilizar um vetor de 50 posições para armazenar os nomes dos 50 alunos.

Uma maneira simples de entender, é imaginar uma gaveta de gavetas ou uma gaveta com diversas repartições. Vetor nada mais é do que uma variável que armazena várias variáveis do mesmo tipo, como mostra a Figura 1 (MANZANO; OLIVEIRA, 2012).

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651623237397-SliEWa7FUW.png)

Para utilizar o vetor é necessário ter uma estrutura de repetição. Neste exemplo, usamos Estrutura PARA.

É necessário declarar o vetor em uma seção de variáveis. Variável é o nome dado ao seu vetor seguido de dois pontos. A palavra vetor é reservada e  indica que esta variável é um vetor com valor inicial e valor final de um tipo (separados por dois pontos), que pode ser inteiro, real, caractere.

**Declaração do Vetor dentro da área de declaração de variáveis:**

VARIÁVEL: vetor [VALOR INICIAL…VALOR FINAL] de TIPO

**Exemplo da declaração:**

nomes: vetor [1…5] de caracter

**Exemplo do Vetor:** armazena 5 nomes de alunos digitados pelo usuário em um vetor

**PARA** contador i 1 **DE** 1 **ATE** 5 **FACA**

   **ESCREVA**("Digite o nome do aluno(a) número ", contadorLoop1, " de 5: ")

   **LEIA**(nomes[contador])

**FIMPARA**

**Exemplo do algoritmo completo (Figura 2):**

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651623287360-oSGREXTFrK.png)

**Exemplo Prático**

Para executar o pseudocódigo utilize o Visualg. No ambiente disponibilizado pela Faculdade Descomplica, basta acessar o ícone do Visualg (Figura 3).

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651623320300-Qozfb9u3pe.png)

​Escreva o algoritmo em pseudocódigo, mostrado na Figura 4, na Área de Algoritmos da ferramenta.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651623352802-8VjY6kzXM9.png)

​Para executar seu algoritmo, é só clicar no ícone “Executar” mostrado na Figura 5, ou F9 do seu teclado.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651623380099-NO3MTzVmvQ.png)

Na Figura 6 vemos a tela de resultado.

  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651623405046-hmZt3a4s2g.png)

**Atividade extra**

Assista ao filme “Jobs (2013)” o Ashton Kutcher interpreta Steve Jobs nesse filme de Joshua Michael Stern, que começa ainda 1976, quando Jobs abandonou a faculdade e deu início a uma revolução junto com seu amigo Steve Wozniak, um gênio da tecnologia. Juntos eles inventaram o primeiro computador pessoal, chamado Apple 1. A narrativa apresenta a personalidade controversa de Jobs e como, apesar de ter mudado o mundo para sempre com a Apple, o fato de ele ter passado por cima dos outros no processo prejudicou sua vida pessoal. Está disponível no catálogo da Amazon Prime Video.

  

  

**Referência Bibliográfica**

- GUEDES, S. (Org.). **Lógica de programação algorítmica**. Pearson: 2014.
- MANZANO, J. A. N. G.; OLIVEIRA, J. F. **Estudo Dirigido de Algoritmos**. 15. ed. São Paulo: Érica, 2012
- PUGA, S.; RISSETTI, G. **Lógica de programação e estruturas de dados, com aplicações em Java.** Pearson: 2016.
- RIBEIRO, J. A. **Introdução à programação e aos algoritmos**. 1. ed. Rio de Janeiro: LTC, 2019


## <mark style="background: #BBFABBA6;">Resumo</mark>

#### 🧰 O Que é um Vetor?

Um vetor é uma **estrutura de dados unidimensional e homogênea**, ou seja, ele armazena múltiplos elementos do mesmo tipo (ex.: todos inteiros ou todos caracteres). Cada elemento é acessado por um índice.

- **Exemplo**: Para armazenar os nomes de 50 alunos, é possível criar um vetor com 50 posições, cada uma reservada para um nome específico.

---

#### 🔄 Como Utilizar um Vetor?

Para manipular vetores, geralmente usamos uma **estrutura de repetição**, como o laço **PARA**, que nos permite acessar cada posição do vetor de forma eficiente.

Exemplo de estrutura **PARA** com vetor:

pseudo

Copiar código

`PARA <variável> DE <valor-inicial> ATE <valor-limite> FACA    <comandos para acessar um vetor> FIMPARA`

#### ✍️ Declaração de um Vetor

A declaração de um vetor é feita na seção de variáveis, onde especificamos o tamanho e o tipo do vetor.

Exemplo:

pseudo

Copiar código

`nomes: vetor [1…5] de caracter`

---

#### 💻 Exemplo Prático no Visualg

O Visualg é uma ótima ferramenta para praticar o uso de vetores. Utilize a estrutura **PARA** para solicitar e armazenar 5 nomes em um vetor.

---

### 🎬 Atividade Extra: Filme "Jobs (2013)"

Assista a esse filme para se inspirar na trajetória de Steve Jobs, desde a fundação da Apple até os desafios de sua vida profissional e pessoal.
## <mark style="background: #FFB86CA6;">Flash Cards</mark>

#flashcards-LógicaDeProgramação

##### Exercícios da Aula

###### GPT

- Vetor::Estrutura de dados unidimensional que armazena elementos do mesmo tipo.
- Índice::Posição usada para acessar um elemento do vetor.
- Estrutura Homogênea::Estrutura onde todos os elementos são do mesmo tipo.
- Declaração de Vetor::Definição de um vetor com tamanho e tipo (ex.: `nomes: vetor [1…5] de caracter`).
- Exemplo de Vetor::Vetor de 5 posições para armazenar nomes de alunos.
- Estrutura PARA::Laço usado para iterar sobre o vetor.
- Exemplo de Estrutura PARA::`PARA i DE 1 A 5 FACA LEIA(nomes[i]) FIMPARA`
- Visualg::Ferramenta para escrever e testar algoritmos em pseudocódigo.