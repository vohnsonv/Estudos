___
Disciplina.: [[Lógica de Programação]]
___
## <mark style="background: #FFF3A3A6;">Aula</mark>

Bem-vindo ao estudo sobre a visão geral da linguagem Java. Este estudo ajudará na compreensão de alguns conceitos e práticas que são importantes no contexto de programação. Vamos conhecer melhor esses conceitos?  

  

**Ambiente Java**

Java é uma linguagem de programação e plataforma computacional lançada pela primeira vez pela Sun Microsystems em 1995. Existem muitas aplicações e sites que não funcionam, a menos que tenha o Java instalado no computador. O Java é rápido, seguro e confiável. É utilizada em notebook a datacenters, consoles de jogos a supercomputadores científicos e telefones celulares à Internet. Além disso, a linguagem de programação que tem sua própria estrutura, regras de sintaxe e paradigma de programação. Deriva da linguagem C, portanto suas regras de sintaxe assemelham-se às regras de C (PUGA e RISSETTI, 2016).

Uma pergunta muito comum entre alunos e iniciantes em programação é “O que é necessário para programar em Java?”. O primeiro passo é configurar seu espaço de trabalho, sendo assim, baixar e instalar o JDK - _Java Runtime Environment_ e posteriormente você pode utilizar um bloco de notas ou o Notepad++ e o prompt de comando (cmd). Nesta disciplina, o bloco de notas e o prompt de comando serão utilizados para as atividades práticas. Abaixo será descrito, resumidamente, alguns componentes que envolvem a programação Java e o JDK.

  

**_Java Runtime Environment_ _- JDK_**  **(Kit de Desenvolvimento Java)**

O JDK é um conjunto de bibliotecas de desenvolvimento de software em linguagem de programação Java. Também estão presentes neste kit o compilador, o interpretador e o JRE - _Java Runtime Environment_ (PUGA e RISSETTI, 2016).

- **Interpretador e Compilador**

Segundo Ribeiro (2016), “_A tradução da linguagem de alto nível em linguagem de máquina pode ser feita de duas maneiras básicas: compilação ou interpretação. No processo de tradução entre a linguagem de alto nível e a linguagem de máquina, o compilador pode encontrar erros de sintaxe; então irá gerar mensagens de erros para que o programador possa corrigi-los. O programa executável somente será gerado quando não houver mais erros de compilação. A compilação é usada em linguagens de programação, como C, C++ e FORTRAN._

_A outra maneira é traduzir linha por linha do programa em linguagem de alto nível para linguagem de máquina, executando uma linha por vez. Neste caso usamos um interpretador. Note que o programa precisa do interpretador para executar, pois as ações ocorrem dentro do ambiente do interpretador. Se houver dados, estes são processados pela execução desta linha no ambiente do interpretador. Se não houver erros, o interpretador lê a próxima linha do programa-fonte e repete o processo até que todas as linhas sejam lidas e o programa chegue ao seu final. Linguagens como Python, Java* e Javascript são interpretadas._”

_*_ **“**_Java é uma linguagem compilada e interpretada. O compilador Java, chamado javac, compila o código-fonte do Java para um código de nível intermediário chamado códigos de bytes_. _Esses códigos de bytes não são diretamente executáveis em qualquer plataforma de hardware existente; mas esses códigos são interpretados pelo interpretador Java, o qual pode operar por si mesmo ou como parte de um navegador Web.”(_IDE, 2021)

- **_Java Runtime Environment_ _- JRE_**

O _Java Runtime Environment_ (também conhecido como o tempo de execução Java) inclui a JVM, bibliotecas de códigos e componentes necessários para executar programas que são escritos na linguagem Java. Está disponível em várias plataformas e está incluído no JDK (PUGA e RISSETTI, 2016).

- **_Java Virtual Machine_ _– JVM_ (Máquina Virtual Java)**

A JVM permite que a linguagem Java seja independente do sistema operacional. O programa desenvolvido nesta linguagem pode ser executado e utilizado no Windows, Linux ou em outros sistemas operacionais. (CÓRDOVA et. Al., 2018).

  

**Meu Primeiro Programa Java**

Para escrever o programa utilize o bloco de notas e para executar utilize o prompt de comando. No ambiente disponibilizado pela Faculdade Descomplica basta acessar o ícone do Bloco de Notas e o do prompt de comando.

  

Assim que abrir o bloco de notas, vamos escrever o código abaixo, salvando o programa Java com o nome MeuPrimeiroProgramaJava.java.

Neste programa, criamos uma classe chamada MeuPrimeiroProgramaJava e dentro da classe o procedimento main com a variável entrada como parâmetro para entrada de dados pelo prompt de comando.

O Java é case sensitive, isso significa que o Java difere letras maiúsculas das minúsculas. É no void main que o programa Java é executado.

Este programa está declarando as variáveis inteiro do tipo int recebendo o valor 47, caracter do tipo char recebendo o valor ‘F’, real do tipo double recebendo o valor 1.65, frase do tipo String recebendo o valor “Lucy Mari’ e VF do tipo boolean recebendo o valor true.

Na linguagem Java, os tipos de dados int, char, double, boolean são tipos primitivos do Java e escritos com letra minúscula. String é um tipo criado, faz parte da biblioteca do Java e, por isso, iniciando sua escrita com letra maiúscula.

O programa verifica se a variável VF tem o valor true. No Java, para a atribuição utiliza-se o símbolo = e para comparação utilização o símbolo ==.

Se o valor de VF é true, ou seja, verdadeiro, o programa imprime uma informação. Utilizamos true e false como valores verdadeiro e falso para as variáveis boleanas no Java.

Utilizamos System.out.print ou System.out.println (este último, pula uma linha após) como um método no Java para saída de resultados, onde a informação será apresentada, para o usuário, via Prompt de Comando.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651697810459-zGNAICXvC6.png)

​Após escrever o programa Java, vá em File -> Save as. Escreva “MeuPrimeiroProgramaJava.java” com essas aspas duplas e selecione all files. Caso você decida desenvolver o programa Java no NotePad++, vá em File -> Save as. Escreve apenas MeuPrimeiroProgramaJava em FileName e escolha, em save as type, Java source file.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651697872613-Ari5QOd9F1.png)

​Abra o Prompt de Comando e verifique em qual pasta você salvou seu arquivo .java. Você pode salvar na pasta users\mcplus\documents, caso deseja.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651697892343-RVtZHBlMW3.png)

No mesmo local onde você salvou seu programa Java, você deve indicar o caminho de onde está o compilável e o executável do Java, para isso, escreva na linha de comando: path “C:\Program Files\Java\jdk1.8.0_111\bin”.

Caso você esteja desenvolvendo no seu ambiente de programação, você precisa verificar qual o endereço de onde está a pasta bin do seu programa Java e realizar o comando do path para configurar o endereço do compilável e do executável do Java.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651697916899-J6NLBe1yej.png)

​Para verificar se seu programa Java está no mesmo diretório que você configurou o caminho do seu executável e compilável, você pode digitar dir *.java na linha de comando do Prompt de comando. E você vai ver a lista dos programas Java neste diretório.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651697938779-QDv02hgKrA.png)

​Agora você já consegue compilar seu programa Java, basta digitar javac, que é o compilador Java e, seguido por um espaço, o nome do seu programa Java, neste caso, MeuPrimeiroProgramaJava.java.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651697963080-PFiJSCfBTV.png)

Se acontecer de aparecer uma lista de erros de compilação, basta voltar ao programa Java e ir resolvendo os erros de compilação. Quando inexistir erros de compilação, significa que o arquivo .class do Java foi criado.

É o arquivo .class que deve ser executado. Neste exemplo, após a compilação, foi criado o arquivo MeuPrimeiroProgramaJava.class. Para verificar se este arquivo foi criado, basta digitar dir *.class.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651697983270-7C7rVRTz3p.png)

Agora que você já verificou que o arquivo .class foi gerado pela compilação do programa Java, você pode usar o comando java MeuPrimeiroProgramaJava (sem a extensão .class) para executar o programa Java.

E, ao executá-lo, na mesma janela do Prompt de Comando, aparece o resultado do programa com a mensagem “Eu sou a Lucy Mari tenho 47 anos e tenho 1.65m de altura.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651698010259-XXzJGTnywC.png)

**Exemplo Prático**

Para este exemplo prático, vamos criar um programa Java que realiza a entrada de dois números inteiros pela linha do Prompt de Comando que são armazenadas no vetor entrada[]. E mostra a saída de resultados pelo Prompt de Comando.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651698030928-Q952EFaCvF.png)

​Este programa Java foi salvo como MeuSegundoProgramaJava.java.​  

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651698068199-8lRjnnznKR.png)

No Prompt de Comando, o programa Java foi compilado com o comando javac MeuSegundoProgramaJava.java e, posteriormente, executado com o comando java MeuSegundoProgramaJava 10 12.

Perceba, neste caso, que os valores 10 e 12, o usuário digitou na linha do Prompt de Comando no momento da execução do programa Java. São os valores de entrada para o programa Java.

Neste caso, o valor “10” foi armazenado em entrada[0] e o valor “12” foi armazenado em entrada[1] no programa Java.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1651698093762-SLXGftawNY.png)

  

  

**Atividade extra**

Assista ao filme “O Dilema das Redes” Este documentário da Netflix foi um dos assuntos muito comentados na pandemia e levou muita gente a repensar sobre manter ou não seus perfis nas redes. O filme explora o perigoso impacto humano das redes sociais, com especialistas em tecnologia alertando sobre os riscos e “armadilhas” de suas próprias criações.

**Referência Bibliográfica**

- CÓRDOVA, R. S.; LEDUR, C. L.; MORAIS, I. S. **Sistemas operacionais**. Porto Alegre: SAGAH, 2018.
- **ORACLE.** Disponível em: [https://www.oracle.com/br/tools/technologies/netbeans-ide.html](https://www.oracle.com/br/tools/technologies/netbeans-ide.html) Ultimo acesso em: Julho de 2021.
- PUGA, S.; RISSETTI, G. **Lógica de programação e estruturas de dados, com aplicações em Java**. Pearson: 2016.
- RIBEIRO, J. A. **Introdução à programação e aos algoritmos**. 1. ed. Rio de Janeiro: LTC, 2019.
- RUSSI, D. F.; CHARÃO, A. S. **Ambientes de Desenvolvimento Integrado no Apoio ao Ensino da Linguagem de Programação Haskell**. Novas Tecnologias na Educação, n. 9, n. 2, 2011.

  
 

  
**Atividade Prática – Aula 13**

**Título da Prática:** Primeiro Exercício em Java

**Aulas Envolvidas nesta Prática:** Visão Geral a Linguagem Java

**Objetivos:** Praticar lógica de programação e desenvolvimento de programas.

**Materiais, Métodos e Ferramentas:** Para realizar este exercício, vamos utilizar Bloco de Notas e Prompt de Comando para criar e testar o programa proposto no desenvolvimento da prática em questão.

**Atividade Prática**  
Com os conhecimentos adquiridos até agora, desenvolva um programa em Java para mostrar alguma informação na tela, seu nome completo, seu curso, sua idade, seu gênero e seu peso.

Após desenvolver seu código conforme a descrição acima, copie e cole na caixa de texto (a resposta da Atividade Prática sempre será em código (Java)).

  
**Gabarito Atividade Prática**

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1661450801167-Iwup756dJI.png)

//nome do programa

//salvar como MeuPrimeiroProgramaJava.java

//nome da classe

class MeuPrimeiroProgramaJava

{

  //módulo principal com a entrada pela linha de comando

  public static void main (String entrada[])

  {

    //declaração de variáveis

    int idade = 47;

    char genero = ‘F’;

    double peso = 50.5;

    String nome =  "Lucy Mari ";

    String curso = "Ciencia da Computacao ";

    System.out.println("Eu sou a " + nome + "tenho " + idade + " anos e tenho " + peso + " kg de peso e curso " + curso);

    System.exit(0);

  }

}

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1661450825676-Fa73CmpMoG.png)

Ir para exercício
## <mark style="background: #BBFABBA6;">Resumo</mark>

#### Visão Geral da Linguagem Java

- **Ambiente Java**: Java é uma linguagem versátil usada em diversas plataformas, de notebooks a supercomputadores. 🌐💻
- **JDK (Kit de Desenvolvimento Java)**: Inclui compilador, interpretador e JRE. Necessário para programar em Java. 🛠️📦
- **Compilação e Interpretação**: Java combina compilação (javac) e interpretação (JVM), tornando-o independente de sistema operacional. 🔄🖥️
- **JRE (Java Runtime Environment)**: Permite executar programas Java em diversas plataformas. 🚀🌍
- **JVM (Java Virtual Machine)**: Garante que programas Java sejam executáveis em diferentes sistemas operacionais. 🧩⚙️

#### Meu Primeiro Programa Java

- **Case Sensitive**: Java diferencia maiúsculas e minúsculas. 🔤
- **Tipos de Dados**: Inclui `int`, `char`, `double`, `boolean` (primitivos) e `String` (não primitivo). 📊
- **Saída**: Usa `System.out.print` ou `System.out.println` para exibir resultados. 🖨️

#### Exemplo Prático

- **Entrada e Saída**: Programas podem receber entradas pelo Prompt de Comando e armazenar em vetores. 💾🖥️

#### Atividade Extra

- Assista ao documentário **"O Dilema das Redes"**, que discute o impacto das redes sociais no comportamento humano. 🎥🌐
## <mark style="background: #FFB86CA6;">Flash Cards</mark>

#flashcards-LógicaDeProgramação

##### Exercícios da Aula

###### GPT

- **Ambiente Java**::Java é uma linguagem de programação versátil usada em diversas plataformas, de notebooks a supercomputadores. 🌐💻
- **JDK**::Kit de Desenvolvimento Java que inclui compilador, interpretador e JRE. 🛠️📦
- **Compilação e Interpretação**::Java combina compilação (javac) e interpretação (JVM) para executar programas. 🔄🖥️
- **JRE**::Java Runtime Environment permite executar programas Java em várias plataformas. 🚀🌍
- **JVM**::Máquina Virtual Java que torna a linguagem independente do sistema operacional. 🧩⚙️
- **Case Sensitive**::Java diferencia maiúsculas de minúsculas no código. 🔤
- **Tipos Primitivos em Java**::`int`, `char`, `double`, `boolean` são tipos de dados básicos. 📊
- **Tipo String**::Tipo não primitivo usado para representar sequências de caracteres. ✍️
- **Saída em Java**::Usa `System.out.print` ou `System.out.println` para exibir resultados no console. 🖨️
- **Entrada pelo Prompt**::Programas Java podem receber entradas pela linha de comando. 💾🖥️
- **Primeiro Programa Java**::Criar e executar programas básicos usando Bloco de Notas e Prompt de Comando. ✏️💻
- **Exemplo Prático**::Entrada de números no Prompt de Comando é armazenada em vetores no programa. 📥➡️📈
- **Atividade Extra**::O documentário "O Dilema das Redes" explora o impacto das redes sociais no comportamento humano. 🎥🌐
- **Compilador Java**::Usa o comando `javac` para compilar programas em Java. 📜🔧
- **Executar Programa Java**::Usa o comando `java <NomeDoPrograma>` para executar. 🚀💻
- **Erro de Compilação**::Corrija erros antes de gerar o arquivo `.class` no Java. 🛠️❌
- **Independência de Plataforma**::Programas Java podem rodar em Windows, Linux e outros sistemas. 🌍🔗