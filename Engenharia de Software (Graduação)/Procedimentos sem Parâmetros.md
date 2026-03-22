___
Disciplina.: [[Lógica de Programação]]
___
## <mark style="background: #FFF3A3A6;">Aula</mark>

Bem-vindo ao estudo sobre Procedimentos! Essa aula ajudará na compreensão de alguns conceitos que são importantes no contexto de programação. Vamos conhecer melhor esses conceitos?

Modularização é a divisão de tarefas. Isso significa que o programa é dividido em partes ou módulos. Estes módulos são blocos de instruções que realizam tarefas específicas. Uma vez carregado, o módulo pode ser executado quantas vezes for necessário. Além disso, pode ser usado para economizar espaço e tempo de programação, já que pode ser chamado em várias partes de um mesmo programa (MANZANO; OLIVEIRA, 2012).

Cada módulo, além de ter acesso às variáveis do programa (variáveis globais), pode ter suas próprias variáveis (variáveis locais), que existem apenas durante sua chamada (RIBEIRO, 2019).

**Algumas vantagens na utilização de módulos**

- Dividir e estruturar um algoritmo em partes logicamente coerentes;
- Facilidade de testar os trechos em separado;
- Evitar repetição do código-fonte;
- Maior legibilidade de um algoritmo.

**Tipos de subprogramas:** Procedimentos e Funções

Neste módulo será mostrado o subprograma Procedimento.

**Procedimento**

Procedimentos são estruturas que agrupam um conjunto de comandos, que são executados quando chamados no decorrer do algoritmo (MANZANO; OLIVEIRA, 2012).

Como um exemplo prático, em VisuAlg, procedimento pode ser definido como subprograma que não retorna nenhum valor. Sua declaração geralmente está no começo do algoritmo e sua sintaxe está descrita abaixo.

```
**Estrutura**

**procedimento** _<nome-de-procedimento>_ [(_<sequência-de-declarações-de-parâmetros>_)]  
// Seção de Declarações de Variáveis Internas  
**inicio**  
// Seção de Comandos  
**fimprocedimento**

**Exemplo**

**PROCEDIMENTO** olaMundo

**VAR**

**INICIO**

      **ESCREVA** (“Olá mundo do procedimento!”)

**FIMPROCEDIMENTO**
```


![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651628441351-khJxjFAzbB.png)

**Exemplo Prático**

Para executar o pseudocódigo utilize o Visualg. No ambiente disponibilizado pela Faculdade Descomplica, basta acessar o ícone do Visualg (Figura 2).

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651628453422-3jJt4LGBJG.png)

​Escreva o algoritmo em pseudocódigo, mostrado na Figura 3, na Área de Algoritmos da ferramenta.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651628471256-qj6d46rGmV.png)

​Para executar o algoritmo, clique no ícone “Executar”, mostrado na Figura 4, ou F9 do seu teclado.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651628484377-wGHCu0Misz.png)

Na Figura 5 vemos a tela de resultado.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651628503417-c0I7O7iuar.png)

  

  

**Atividade extra**

Assista ao filme “Piratas da Informática” Parcialmente baseado no livro “Fire in the Valley: The Making of the Personal Computer”, escrito por Paul Feiberger e Michael Swaine, o filme de Martyn Burke narra a ascensão da Apple e Microsoft, mostrando a conflituosa relação de Steve Jobs (Noah Wyle) e Bill Gates (Anthony Michael Hall) nos bastidores.

  

  

**Referência Bibliográfica**

- GUEDES, S. (Org.). **Lógica de programação algorítmica**. Pearson: 2014.
- MANZANO, J. A. N. G.; OLIVEIRA, J. F. **Estudo Dirigido de Algoritmos**. 15. ed. São Paulo: Érica, 2012
- PUGA, S.; RISSETTI, G. **Lógica de programação e estruturas de dados, com aplicações em Java**. Pearson: 2016.
- RIBEIRO, J. A. **Introdução à programação e aos algoritmos**. 1. ed. Rio de Janeiro: LTC, 2019

**Atividade Prática – Aula 9**

  
**Título da Prática:** Multiplicação como uso de Procedimento

  
**Aulas Envolvidas nesta Prática:** Procedimentos

  
**Objetivos:** Praticar lógica de programação e desenvolvimento de algoritmos.  
 

**Materiais, Métodos e Ferramentas:** Para realizar este exercício, vamos utilizar Visualg para testar o algoritmo proposto no desenvolvimento da prática em questão.

**Atividade Prática**  
Com os conhecimentos adquiridos até agora, desenvolva um algoritmo em pseudocódigo que multiplique 2 números digitados pelo usuário. Mostre o resultado na tela. (Use procedimento para o cálculo)

Após desenvolver seu código conforme a descrição acima, copie e cole na caixa de texto (a resposta da Atividade Prática sempre será em código (pseudocódigo)).

**Gabarito Atividade Prática**

​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1661450343712-KVbcYHL20t.png)
## <mark style="background: #BBFABBA6;">Resumo</mark>

1. **Modularização**  
    Modularização é o processo de dividir um programa em partes ou módulos, cada um com tarefas específicas, para maior eficiência e organização. 🔄🛠️
    
2. **Vantagens da Modularização**
    
    - Melhor divisão e estruturação do algoritmo.
    - Facilidade de testar módulos individualmente.
    - Evita repetição de código.
    - Melhora a legibilidade do algoritmo. 📑✅
3. **Tipos de Subprogramas**  
    Subprogramas se dividem em procedimentos e funções. Este módulo foca nos procedimentos. ✂️📚
    
4. **Procedimento**
    
    - Agrupamento de comandos executados quando chamados.
    - Não retorna valores.
    - Declarado no início do algoritmo. 🔢📝
5. **Estrutura de um Procedimento**
    
    less
    
    Copiar código
    
    `procedimento <nome-de-procedimento> [(<parâmetros>)]   // Variáveis internas   inicio   // Comandos   fimprocedimento`  
    
    🖥️🔧
    
6. **Exemplo**
    
    java
    
    Copiar código
    
    `procedimento olaMundo   inicio       escreva("Olá mundo do procedimento!")   fimprocedimento`  
    
    🌍✍️
    
7. **Execução no Visualg**
    
    - Escreva o pseudocódigo na área do algoritmo.
    - Use o botão "Executar" ou pressione **F9**. 🔄🖱️
8. **Atividade Extra**  
    Assista ao filme _Piratas da Informática_, explorando a ascensão da Apple e Microsoft. 🎥🖥️
    
9. **Atividade Prática**  
    Desenvolver um algoritmo que multiplica dois números digitados pelo usuário, usando um procedimento para cálculo. ➗🖩
    

#### **Dica Final**

Modularize para simplificar! Procedimentos tornam a programação mais limpa e eficiente. 🚀🎯
## <mark style="background: #FFB86CA6;">Flash Cards</mark>

#flashcards-LógicaDeProgramação

##### Exercícios da Aula

###### GPT

- **Modularização**::Divisão de um programa em módulos com tarefas específicas para maior eficiência e organização. 🔄🛠️
- **Vantagens da Modularização**::Estruturação lógica, facilidade de teste, legibilidade aprimorada e evita repetição de código. 📑✅
- **Subprogramas**::Incluem procedimentos e funções; procedimentos não retornam valores. ✂️📚
- **Procedimento**::Agrupamento de comandos executados quando chamados, sem retorno de valores. 🔢📝
- **Estrutura de Procedimento**::Inclui declaração, variáveis internas, comandos e encerramento com `fimprocedimento`. 🖥️🔧
- **Exemplo de Procedimento**::Código que agrupa tarefas específicas, como "Olá Mundo!". 🌍✍️
- **Execução no Visualg**::Escreva o algoritmo na área designada e use "Executar" ou pressione F9. 🔄🖱️
- **Atividade Extra**::Filme "Piratas da Informática" para explorar a história da Apple e Microsoft. 🎥🖥️
- **Atividade Prática**::Algoritmo que multiplica dois números digitados pelo usuário com uso de procedimento. ➗🖩
- **Benefício dos Procedimentos**::Torna a programação mais limpa, eficiente e modular. 🚀🎯