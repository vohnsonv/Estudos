___
Disciplina.: [[Lógica de Programação]]
___
## <mark style="background: #FFF3A3A6;">Aula</mark>

Bem-vindo ao estudo sobre Funções! Essa aula ajudará na compreensão de alguns conceitos que são importantes no contexto de programação. Vamos conhecer melhor esses conceitos?

Modularização é a divisão de tarefas. Ou seja, o programa é dividido em partes ou módulos. Estes módulos são blocos de instruções que realizam tarefas específicas. Uma vez carregado, o módulo pode ser executado quantas vezes for necessário. Além disso, pode ser usado para economizar espaço e tempo de programação, já que pode ser chamado em várias partes de um mesmo programa (MANZANO; OLIVEIRA, 2012).

Cada módulo, além de ter acesso às variáveis do programa (variáveis globais), pode ter suas próprias variáveis (variáveis locais), que existem apenas durante sua chamada (RIBEIRO, 2019).

**Algumas vantagens na utilização de módulos**

- Dividir e estruturar um algoritmo em partes logicamente coerentes;
- Facilidade de testar os trechos em separado;
- Evitar repetição do código-fonte;
- Maior legibilidade de um algoritmo.

**Tipos de subprogramas:** Procedimentos e Funções

Neste módulo será mostrado o subprograma Funções.

**Funções**

Função é um tipo especial de procedimento no qual, depois de executada a chamada, o valor calculado é retornado no nome da função, que passa a ser uma variável da expressão (RIBEIRO, 2019).

Num exemplo prático, em VisuAlg, a função é um subprograma que retorna um valor. De modo análogo aos procedimentos, sua declaração geralmente está no começo do algoritmo e sua sintaxe está descrita abaixo.

```
**Estrutura**

**funcao** _<nome-de-função>_ [(_<sequência-de-declarações-de-parâmetros>_)]: _<tipo-de-dado>_  
// Seção de Declarações Internas  
**inicio**  
// Seção de Comandos

**retorne** <valor>  
**fimfuncao**

**Exemplo**

**FUNCAO** olaMundo:caracter

**VAR**

  frase:caracter

**INICIO**

  frase<-”Olá Mundo!”

  **RETORNE** frase  

**FIMFUNCAO**
```

**Exemplo Completo (Figura 1)**

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651668989318-6bVgG6ut5O.png)

**Exemplo Prático**

Para executar o pseudocódigo utilize o Visualg, no ambiente disponibilizado pela Faculdade Descomplica, basta acessar o ícone do Visualg (Figura 2).

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651669342808-Kmnox2tyHu.png)

​Escreva o algoritmo em pseudocódigo, mostrado na Figura 3, na Área de Algoritmos da ferramenta.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651669371974-Nzj2QWpp2Z.png)

​Para executar seu algoritmo, clique no ícone “Executar” mostrado na Figura 4, ou F9 do seu teclado.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651669397776-D1JKqXKsBq.png)

Na Figura 5 vemos a tela de resultado.

  

  

  

**Atividade extra**

Assista ao filme “A Rede Social” Vencedor de três Oscars e quatro Globos de Ouro, o longa de David Fincher narra a trajetória de Mark Zuckerberg na criação do Facebook nos seus tempos de estudante na Universidade Harvard. Em seis anos ele se torna o mais jovem bilionário da história, tamanho o sucesso da rede social. Mas, apesar da fortuna e dos 500 milhões de amigos online,  sua ascensão sem precedentes traz problemas legais e também  pessoais.

**Referência Bibliográfica**

- GUEDES, S. (Org.). **Lógica de programação algorítmica**. Pearson: 2014.
- MANZANO, J. A. N. G.; OLIVEIRA, J. F. **Estudo Dirigido de Algoritmos**. 15. ed. São Paulo: Érica, 2012
- PUGA, S.; RISSETTI, G. **Lógica de programação e estruturas de dados, com aplicações em Java**. Pearson: 2016.
- RIBEIRO, J. A. **Introdução à programação e aos algoritmos**. 1. ed. Rio de Janeiro: LTC, 2019

  

  

**Atividade Prática – Aula 11**

**Título da Prática:** Multiplicação com o uso de Função

**Aulas Envolvidas nesta Prática:** Função

**Objetivos:** Praticar lógica de programação e desenvolvimento de algoritmos.

**Materiais, Métodos e Ferramentas:** Para realizar este exercício, vamos utilizar Visualg para testar o algoritmo proposto no desenvolvimento da prática em questão.

**Atividade Prática**  
Com os conhecimentos adquiridos até agora, desenvolva um algoritmo em pseudocódigo que multiplique 2 números digitados pelo usuário (utilize função sem parâmetros para o cálculo). Mostre o resultado na tela. 

Após desenvolver seu código conforme a descrição acima, copie e cole na caixa de texto (a resposta da Atividade Prática sempre será em código (pseudocódigo)).

**Gabarito Atividade Prática**
## <mark style="background: #BBFABBA6;">Resumo</mark>

**Resumo sobre Funções sem Parâmetros** 🌟

- **Modularização**: Divisão de tarefas em partes chamadas módulos que executam tarefas específicas, economizando tempo e espaço. 🔄🛠️
- **Vantagens**: Facilita a estruturação do algoritmo, testes, evita repetição de código e aumenta a legibilidade. ✅📋
- **Função**: Tipo especial de subprograma que retorna um valor após ser executado. 🎯📤
- **Estrutura**:
    
    php
    
    Copiar código
    
    `funcao <nome>():<tipo>   inicio   retorne <valor>   fimfuncao`  
    
- **Exemplo**:
    
    arduino
    
    Copiar código
    
    `funcao olaMundo:caracter   inicio     retorne "Olá Mundo!"   fimfuncao`  
    
- **Execução no Visualg**: Escreva o pseudocódigo e execute clicando em "Executar" ou pressione F9. 💻
- **Atividade Prática**: Desenvolver uma função que multiplique dois números sem usar parâmetros. ✍️
- **Atividade Extra**: Assistir ao filme **"A Rede Social"** para refletir sobre inovação e desafios. 🎥
## <mark style="background: #FFB86CA6;">Flash Cards</mark>

#flashcards-LógicaDeProgramação

##### Exercícios da Aula

###### GPT

- **Modularização::Divisão de tarefas em partes chamadas módulos, que realizam tarefas específicas. 🔄🛠️**
- **Vantagens da Modularização::Facilidade de teste, evita repetição, aumenta legibilidade e estrutura o algoritmo. ✅📋**
- **Função::Subprograma que retorna um valor após ser executado. 🎯📤**
- **Estrutura de uma Função::Inicia com `funcao`, declarações internas, comandos e retorna um valor. 📜🔄**
- **Exemplo de Função::`funcao olaMundo:caracter inicio retorne "Olá Mundo!" fimfuncao` 💻**
- **Execução no Visualg::Escreva o código e clique em "Executar" ou pressione F9. 🚀**
- **Uso de Funções::Permite reaproveitamento de código e simplificação do programa. 🔁📋**