___
Disciplina.: [[Lógica de Programação]]
___
## <mark style="background: #FFF3A3A6;">Aula</mark>

Bem-vindo ao estudo sobre as Matrizes! Essa aula ajudará na compreensão de alguns conceitos que são importantes no contexto de programação. Vamos conhecer melhor esses conceitos?

Uma matriz é uma variável composta, homogênea e multidimensional, formada por uma sequência de variáveis do mesmo tipo, com o mesmo identificador (mesmo nome) e alocadas sequencialmente na memória (RIBEIRO, 2019).

Pode-se dizer que matriz é um vetor de vetores. A diferença é que um vetor tem apenas uma dimensão, enquanto a matriz possui mais de uma dimensão. Ambos são acessados por índice.

As matrizes são comumente referenciadas através de suas dimensões, ou seja, são referenciadas pelas quantidades de **linhas** e **colunas****,** como mostra a Figura 1 (MANZANO; OLIVEIRA, 2012).

Sua notação comum é **MxN**, onde:

**M** é a dimensão horizontal (quantidade de **linhas**).

**N** é dimensão vertical (quantidade de **colunas**).

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651628661285-hNXrxAPDJw.png)

Imagine o seguinte problema: Você precisa criar um algoritmo que lê e armazena as notas parciais; calcula e armazena a média; e, por fim, informa o resultado.

No problema apresentado, é possível utilizar matrizes com várias posições para armazenar as notas para o cálculo da média e, posteriormente, mostrar o resultado. Na figura 2 é mostrado um exemplo de matriz.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651628692877-HsyDtZuax2.png)

Para utilizar uma matriz é necessário usar duas estruturas de repetição do tipo PARA, uma para linha e outra para coluna. Vejamos a seguir:

![[Pasted image 20241208200212.png]]

É necessário declarar a matriz em uma seção de variáveis, mas é importante saber que não será escrito “matriz” e sim “vetor” na declaração do seu algoritmo, que será executado no Visualg. Variável é o nome dado a sua matriz, seguido de dois pontos e da palavra vetor, que é reservada e indica que esta variável é um vetor com valor inicial e valor final da linha e da coluna de um tipo, que pode ser inteiro, real, caractere.

**Declaração da Matriz dentro da área de declaração de variáveis:**

 VARIÁVEL: vetor [VALOR INICIAL L…VALOR FINAL L, VALOR INICIAL  C…VALOR FINAL C] de TIPO

**Exemplo da declaração:**

notas: vetor [1…50,1…4] de inteiro

**Exemplo de Matriz:**

**PARA contador** i 1 **DE** 1 **ATE** 50 **FACA**

   **ESCREVA(**“Aluno(a) número ", i**)**

   **PARA contador** j 1 **DE** 1 **ATE** 4 **FACA**

       **ESCREVA(**"Digite a nota: ", j**)**

       **LEIA(**notas[i , j]**)**

   **FIMPARA**

**FIMPARA**

**Exemplo do algoritmo completo (Figura 2)**

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651628732100-PrLmLafBEa.png)

**Exemplo Prático**

Para executar o pseudocódigo utilize o Visualg. No ambiente disponibilizado pela Faculdade Descomplica, basta acessar o ícone do Visualg (Figura 3).

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651628783500-WG9s5wu2E9.png)

Escreva o algoritmo em pseudocódigo, mostrado na Figura 4, na Área de Algoritmos da ferramenta.

  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651628929163-OWnECN21Wa.png)

​Para executar seu algoritmo, basta clicar no ícone “Executar” mostrado na Figura 5, ou F9 do seu teclado.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651628981433-NOUwOQmrAa.png)

​Na Figura 6 observamos a tela de resultado.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651629063973-iW5awISSNP.png)

**Atividade extra**

Assista ao filme “Matrix” Esse filme, primeiro de sua trilogia, nos mostra um mundo dominado pelas máquinas no qual Neo (Keanu Reeves), que trabalha como um hacker, descobre que ele e toda a raça humana vivem na verdade dentro da Matrix, um programa de computador.

**Referência Bibliográfica**

- GUEDES, S. (Org.). **Lógica de programação algorítmica**. Pearson: 2014.
- MANZANO, J. A. N. G.; OLIVEIRA, J. F. **Estudo Dirigido de Algoritmos**. 15. ed. São Paulo: Érica, 2012
- PUGA, S.; RISSETTI, G. **Lógica de programação e estruturas de dados, com aplicações em Java.** Pearson: 2016.
- RIBEIRO, J. A. **Introdução à programação e aos algoritmos**. 1. ed. Rio de Janeiro: LTC, 2019

**Atividade Prática – Aula 8**

**Título da Prática:** Soma de Matriz

**Aulas Envolvidas nesta Prática:** Matriz

**Objetivos:** Praticar lógica de programação e desenvolvimento de algoritmos.

**Materiais, Métodos e Ferramentas:** Para realizar este exercício, vamos utilizar Visualg para testar o algoritmo proposto no desenvolvimento da prática em questão.

**Atividade Prática**  
Com base no exemplo abaixo e com os conhecimentos adquiridos até agora, desenvolva um algoritmo em pseudocódigo com uma matriz 5x5 que some cada valor de uma posição da matriz com 10. Mostre o resultado na tela.   
Exemplo:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1661450075564-Goj6VP30j4.png)

Após desenvolver seu código conforme a descrição acima, copie e cole na caixa de texto (a resposta da Atividade Prática sempre será em código (pseudocódigo)).

Gabarito Atividade Prática

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1661450116194-eHCrXpDwep.png)

## <mark style="background: #BBFABBA6;">Resumo</mark>

### Matrizes: Conceitos e Aplicações 📊🤓

**1. O que é uma Matriz?**

- Uma matriz é uma **variável composta**, homogênea e multidimensional. É como um vetor de vetores. ➡️📦
- Representada como M×NM \times NM×N, onde:
    - **M**: número de linhas (horizontal). 📏
    - **N**: número de colunas (vertical). 📐

---

**2. Exemplos Práticos**

- Usada para armazenar dados como **notas de alunos**, facilitando cálculos e exibição. 📋📝

---

**3. Estrutura de Repetição**

- Matrizes são acessadas com **duas estruturas PARA**:
    
    pseudocode
    
    Copiar código
    
    `PARA linha DE 1 ATÉ M FACA   PARA coluna DE 1 ATÉ N FACA     Acesse matriz[linha, coluna]   FIMPARA FIMPARA`
    
- Isso permite iterar sobre todas as posições da matriz. 🔄💻

---

**4. Declaração no Visualg**

- Sintaxe para declarar matrizes no Visualg:
    
    pseudocode
    
    Copiar código
    
    `VARIÁVEL: vetor [VALOR_INICIAL_L..VALOR_FINAL_L, VALOR_INICIAL_C..VALOR_FINAL_C] de TIPO`
    
    **Exemplo:**
    
    pseudocode
    
    Copiar código
    
    `notas: vetor [1..50, 1..4] de inteiro`
    

---

**5. Exemplo de Algoritmo**

- Leitura de notas de 50 alunos, com 4 notas cada:
    
    pseudocode
    
    Copiar código
    
    `PARA i DE 1 ATÉ 50 FACA   ESCREVA("Aluno ", i)   PARA j DE 1 ATÉ 4 FACA     ESCREVA("Digite a nota ", j)     LEIA(notas[i, j])   FIMPARA FIMPARA`
    

📖➡️📈

---

**6. Atividade Prática** 🖥️

- Desenvolver algoritmo que cria uma matriz 5×55 \times 55×5, adiciona **10** a cada elemento, e exibe o resultado na tela. ✍️➕🔟

---

**7. Ferramentas Recomendadas**

- **Visualg**: Para testar algoritmos em pseudocódigo. 💻

---

**Dica Extra** 🎥🍿

- Assista ao filme **"Matrix"** para uma visão divertida sobre o tema!
## <mark style="background: #FFB86CA6;">Flash Cards</mark>

#flashcards-LógicaDeProgramação

##### Exercícios da Aula

###### GPT

- **Uso Prático de Matrizes::** Ideal para armazenar dados como notas, cálculos e exibição de resultados. 📋📈
- **Atividade Prática::** Criar uma matriz 5×55 \times 55×5, adicionar 10 a cada elemento e mostrar o resultado. 🔟
- **Ferramenta Visualg::** Ambiente para criar e testar pseudocódigos com matrizes. 🖥️🧪
- **Dica Divertida::** Assista ao filme _Matrix_ para associar conceitos de programação de forma criativa! 🎥🍿
- **Matriz::** Variável composta, homogênea e multidimensional, semelhante a um vetor de vetores. 📦📏
- **Matriz M×NM \times NM×N::** MMM: número de linhas, NNN: número de colunas. 📐
- **Declaração no Visualg::** `VARIÁVEL: vetor [VALOR_INICIAL_L..VALOR_FINAL_L, VALOR_INICIAL_C..VALOR_FINAL_C] de TIPO`. 💻
- **Exemplo de Declaração::** `notas: vetor [1..50, 1..4] de inteiro`. ✍️
- **Estrutura PARA com Matrizes::** Necessário usar dois laços PARA, um para linhas e outro para colunas. 🔄
