___
Disciplina.: [[Lógica de Programação]]
___
## <mark style="background: #FFF3A3A6;">Aula</mark>

Bem-vindo ao estudo sobre Procedimentos, agora utilizando Parâmetros! Essa aula ajudará na compreensão de alguns conceitos que são importantes no contexto de programação. Vamos conhecer melhor esses conceitos?

Modularização é a divisão de tarefas. Ou seja, o programa é dividido em partes ou módulos. Estes módulos são blocos de instruções que realizam tarefas específicas. Uma vez carregado, o módulo pode ser executado quantas vezes for necessário. Além disso, pode ser usado para economizar espaço e tempo de programação, já que pode ser chamado em várias partes de um mesmo programa (MANZANO; OLIVEIRA, 2012).

Cada módulo, além de ter acesso às variáveis do programa (variáveis globais), pode ter suas próprias variáveis (variáveis locais), que existem apenas durante a sua chamada (RIBEIRO, 2019).

**Algumas vantagens na utilização de módulos**

- Dividir e estruturar um algoritmo em partes logicamente coerentes;
- Facilidade de testar os trechos em separado;
- Evitar repetição do código-fonte;
- Maior legibilidade de um algoritmo.

**Tipos de subprogramas:** Procedimentos e Funções

Neste módulo será mostrado o subprograma Procedimento com Parâmetro.

**Procedimento** **com Parâmetro**

Procedimentos são estruturas que agrupam um conjunto de comandos, que são executados quando chamados no decorrer do algoritmo (MANZANO; OLIVEIRA, 2012).

Como um exemplo prático, em VisuAlg, procedimento pode ser definido como subprograma que não retorna nenhum valor, mas, nesse caso, recebe um valor pelo parâmetro. Sua declaração geralmente está no começo do algoritmo e sua sintaxe está descrita abaixo.

```
**Estrutura**

**procedimento** _<nome-de-procedimento>_ [(_<sequência-de-declarações-de-parâmetros>_)]  
// Seção de Declarações Internas  
**inicio**  
// Seção de Comandos  
**fimprocedimento**

**Exemplo**

**PROCEDIMENTOS** olaMundo(frase:caracter)

**VAR**

**INICIO**

      **ESCREVA** (frase)

**FIMPROCEDIMENTO**
```

**Exemplo Completo (Figura 1)**

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651666578166-m1OkMzBuXe.png)

**Exemplo Prático**

Para executar o pseudocódigo utilize o Visualg. No ambiente disponibilizado pela Faculdade Descomplica, basta acessar o ícone do Visualg (Figura 2).

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651666617346-mWcVnzR23G.png)

​Escreva o algoritmo em pseudocódigo da Figura 3 na Área de Algoritmos da ferramenta.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651666672039-0EdnSydoXC.png)

​Para executar o algoritmo, clique no ícone “Executar” mostrado na Figura 4 ou a F9 do seu teclado.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651666699388-0Bt85quWkQ.png)

Na Figura 5 vemos a tela de resultado.

  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651666729067-j2L88w7xSH.png)

**Atividade extra**

Assista ao filme “Chappie (2015) ”Essa obra de ação conta as aventuras e perigos de um jovem cientista ao finalmente dotar um robô com inteligência artificial. Tudo começa a sair do controle quando alguns criminosos de uma gangue conseguem roubar o robô, e ele passa a aprender as “coisas da vida” sozinho.

O filme é interessante por tocar em vários pontos delicados sobre o assunto, levando-nos a refletir sobre as infinitas possibilidades e riscos ao se conceder inteligência às máquinas. Com o avanço crescente e cada vez veloz da tecnologia, propiciar que os estudantes de Ciência da Computação pensem a respeito dessas questões é um ponto forte do filme.

**Referência Bibliográfica**

- GUEDES, S. (Org.). **Lógica de programação algorítmica**. Pearson: 2014.
- MANZANO, J. A. N. G.; OLIVEIRA, J. F. **Estudo Dirigido de Algoritmos**. 15. ed. São Paulo: Érica, 2012
- PUGA, S.; RISSETTI, G. **Lógica de programação e estruturas de dados, com aplicações em Java**. Pearson: 2016.
- RIBEIRO, J. A. **Introdução à programação e aos algoritmos**. 1. ed. Rio de Janeiro: LTC, 2019
## <mark style="background: #BBFABBA6;">Resumo</mark>

**Resumo sobre Procedimentos com Parâmetros** 🚀📚

- **Modularização**: Divisão de tarefas para maior organização e eficiência em programas. 🔄🛠️
- **Vantagens dos módulos**:
    - Estruturar algoritmos de forma lógica; 🧩
    - Facilitar testes individuais; ✅
    - Evitar repetições no código; 🖋️
    - Melhorar a legibilidade do programa. 👓
- **Procedimentos com Parâmetros**: Agrupam comandos que podem receber valores (parâmetros) para uso na execução. 🎯📤
- **Exemplo de estrutura**:
    
    php
    
    Copiar código
    
    `procedimento <nome> (<parâmetros>)   inicio   <comandos>   fimprocedimento`  
    
- **Exemplo prático**: Procedimento `olaMundo(frase:caracter)` que recebe e exibe uma mensagem na tela. ✍️💻
- **Execução no Visualg**:
    - Acesse a ferramenta; 🖥️
    - Escreva o código no editor;
    - Execute com o botão "Executar" ou F9. 🔄🖱️
- **Atividade Extra**: Assista ao filme **"Chappie" (2015)** para refletir sobre inteligência artificial e seus desafios. 🤖🎥
## <mark style="background: #FFB86CA6;">Flash Cards</mark>

#flashcards-LógicaDeProgramação

##### Exercícios da Aula

###### GPT

- **Modularização**::Divisão de tarefas em partes menores ou módulos para maior organização. 🔄🛠️
- **Vantagem - Estruturação**::Permite estruturar algoritmos de forma lógica e coerente. 🧩
- **Vantagem - Testes**::Facilita o teste individual de cada parte do programa. ✅
- **Vantagem - Reutilização**::Evita repetição de código, permitindo reutilização. 🖋️
- **Vantagem - Legibilidade**::Melhora a compreensão e legibilidade do algoritmo. 👓
- **Procedimento com Parâmetro**::Subprograma que recebe valores (parâmetros) para execução. 🎯📤
- **Estrutura de Procedimento**::`procedimento <nome> (<parâmetros>) ... fimprocedimento`. ✍️
- **Exemplo - Procedimento**::`olaMundo(frase:caracter)` exibe a mensagem recebida. 💬💻
- **Execução no Visualg**::Escreva o código, clique em "Executar" ou pressione F9. 🔄🖱️