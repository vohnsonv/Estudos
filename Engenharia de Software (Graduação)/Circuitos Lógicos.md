___
Disciplina.: [[Arquitetura de Computadores]]
___
## <mark style="background: #FFF3A3A6;">Aula</mark>

**1– Portas lógicas**

**Portas** lógicas são dispositivos que operam e trabalham com sinais lógicos de entrada para produzir uma e somente uma saída.

São usadas em circuitos eletrônicos, por causa das situações que os sinais deste tipo de circuito podem apresentar: presença de sinal, “1”; e ausência de sinal, ou “0”.

As portas lógicas são componentes básicos da eletrônica digital.

Portas lógicas são usadas para criar circuitos digitais e até mesmo circuitos integrados complexos.

Em eletrônica digital apenas dois níveis são permitidos, os níveis  “0” ou “1”.

Existem diversas portas lógicas, estudaremos as principais:

AND, OR, NOR, NAND, NOT e XOR

**Porta AND**

A porta AND tem a representação a seguir e o seguinte sinal de saída de acordo com suas entradas:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668188410144-wrjySstFxJ.png)

A porta AND lembra a operação de multiplicação.

Observe abaixo um Ilustração da porta AND. Nesta ilustração temos as chaves A e B. A lâmpada irá se acender apenas se tanto a chave A e a chave B estiverem fechadas, neste caso, saída C igual a 1. Se uma das portas estiver aberta, a lâmpada não acenderá, isto é, C com sinal igual a 0.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668188430199-YFuF9iiqUW.png)

**Porta OR**

A porta OR tem a representação a seguir, além do seguinte sinal de saída de acordo com suas entradas:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668188451241-qHb7ZnClLL.png)

A porta OR lembra a operação de soma.

Observe abaixo uma ilustração da porta OR. Nesta ilustração temos as chaves A e B. A lâmpada irá se acender se a chave A estiver fechada ou se a chave B estiver fechada. Se ambas estiverem fechadas também a lâmpada acenderá, neste caso, saída C igual a 1. Se ambas as portas estiverem abertas, a lâmpada não acenderá, isto é, C terá sinal igual a 0.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668188480439-RuLdzhbHqA.png)

**Porta NOT, NAND e NOR**

A porta NOT tem a representação a seguir, além do seguinte sinal de saída de acordo com suas entradas:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668188518601-4V2BsfaMnX.png)

Observe que a porta NOT simplesmente inverte o sinal de entrada.

A porta NOT pode se combinar com a porta AND formando a porta NOT AND ou NAND.

O comportamento dela se dá de acordo com a representação e a tabela abaixo:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668188539926-Q7Wyqcje2h.png)

A porta NOT pode se combinar com a porta OR formando a porta NOT OR ou NOR.

O comportamento dela se dá de acordo com a representação e a tabela abaixo:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668188553014-Rn6v4ZvOxH.png)

**Porta XOR**

A porta XOR tem a representação a seguir e o seguinte sinal de saída de acordo com suas entradas:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668188605441-TXI4nMDbxW.png)

Note como a saída da porta XOR é 1 se, e somente se, as entradas tiverem sinais diferentes entre si (uma 0 e outra 1).

Pode-se inverter a saída XOR acoplando a ela uma NOT, isso resulta na porta XNOR, neste caso, entradas diferentes irão gerar saída 0.

Resumindo a simbologia das portas lógicas vistas até aqui temos:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668188625742-3YmMmS4CpX.png)

Considerando os valores de entrada e saída, temos a seguinte síntese das portas lógicas:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668188643891-0xDlxcxDEG.png)

**2 - Circuitos Lógicos**

Associando portas lógicas umas às outras temos a composição de circuitos lógicos. Dispositivos digitais podem ser vistos como combinação de muitos circuitos lógicos/digitais.

O circuito abaixo é composto por duas portas lógicas e três sinais digitais de entrada, A, B e C.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668188664542-9EInibsY9P.png)

Note que para três sinais digitais temos oito possíveis combinações de entradas: 000, 001, 010, 100, 101, 011, 110 e 111. Por esse motivo, a tabela que representa todos os possíveis comportamentos do circuito deve ter 8 linhas dedicadas às combinações de entrada.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668188693708-SSt0k6X5JC.png)

Outro ponto a destacar é que neste circuito a saída de uma porta OR é um sinal de entrada de uma porta AND.

Observe que a expressão matemática A(B+C) representa a saída do circuito, considerando os sinais A, B e C.

Interessante notar que a expressão A(B+C) = AB + AC.

Neste caso, a expressão AB + AC sugere outro circuito de comportamento equivalente ao primeiro.

Para isso, tomemos três portas lógicas associadas conforme abaixo. Note como a saída é rigorosamente a mesma do circuito anterior, embora tenha três portas lógicas e o primeiro duas portas lógicas.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668188718257-bD9IhBBkut.png)

**Dica:**

Simuladores de circuitos lógicos são extremamente úteis em projetos de circuitos. Com base na tabela-verdade (tabela com 0´s e 1´s) constrói-se um circuito ou, desenhando o circuito, o programa apresenta a tabela correspondente.

Um dos simuladores interessantes disponíveis é o _Logic Gate Simulator_ ([https://academo.org/demos/logic-gate-simulator/](https://academo.org/demos/logic-gate-simulator/)).

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668188747503-BYm8AuRM2J.png)

Referências Bibliográficas

BROOKSHEAR, J.G. **Ciência da Computação: uma visão abrangente.** Porto Alegre: Bookman, 2013.

FORBELLONE, A.L.V. & EBERSPACHER, H. F.  **Lógica de Programação –  A Construção de Algoritmos e Estruturas de Dados**. 3ª. Edição. São Paulo, SP: Prentice Hall, 2005.
## <mark style="background: #BBFABBA6;">Resumo</mark>

### 🤓 Introdução a Circuitos Lógicos e Portas Lógicas 🔌

#### 🧰 O Que São Portas Lógicas?

Portas lógicas são componentes fundamentais da eletrônica digital. Elas processam sinais lógicos (0 e 1) para produzir uma única saída com base em combinações de entrada. Exemplos de portas lógicas:

- **AND**: Multiplicação lógica (saída é 1 apenas se todas as entradas forem 1).
- **OR**: Soma lógica (saída é 1 se ao menos uma entrada for 1).
- **NOT**: Inversão lógica (0 vira 1 e 1 vira 0).
- **NAND**: Combinação de NOT e AND (inversão da saída AND).
- **NOR**: Combinação de NOT e OR (inversão da saída OR).
- **XOR**: Exclusão lógica (saída é 1 se apenas uma entrada for 1).
- **XNOR**: Exclusão lógica inversa (saída é 1 se as entradas forem iguais).

---

### 🔄 Circuitos Lógicos

Circuitos lógicos são formados ao conectar portas lógicas. Eles representam combinações complexas de sinais, com base na tabela-verdade.

- **Exemplo de Circuito**:
    - Entrada: A, B, C.
    - Saída: A(B+C) ou AB + AC.
    - Tabela-verdade: Todas as combinações possíveis de entrada (000 a 111).

---

### 🛠️ Simuladores de Circuitos Lógicos

Simuladores, como o **Logic Gate Simulator**, ajudam na criação e análise de circuitos lógicos. Com base em tabelas-verdade, é possível construir circuitos e verificar comportamentos.
## <mark style="background: #FFB86CA6;">Flash Cards</mark>

#flashcards-ArquiteturaDeComputadores

##### Exercícios da Aula

###### GPT

- Portas Lógicas::Dispositivos que processam sinais lógicos para gerar uma saída única. 🔌
- Sinais Lógicos::Níveis binários 0 (ausência de sinal) e 1 (presença de sinal). 🔢
- Porta AND::Saída 1 se todas as entradas forem 1 (multiplicação lógica). ✖️
- Porta OR::Saída 1 se ao menos uma entrada for 1 (soma lógica). ➕
- Porta NOT::Inverte o sinal de entrada (0 vira 1 e 1 vira 0). 🔄
- Porta NAND::Combinação de NOT e AND (inversão da saída AND). ✖️🔄
- Porta NOR::Combinação de NOT e OR (inversão da saída OR). ➕🔄
- Porta XOR::Saída 1 se as entradas forem diferentes (exclusão lógica). ❌
- Porta XNOR::Saída 1 se as entradas forem iguais (exclusão lógica inversa). ✅
- Circuitos Lógicos::Combinações de portas lógicas que processam sinais. 🖧
- Tabela-Verdade::Lista todas as combinações possíveis de entrada e saída. 📋
- Simulador de Circuitos::Ferramenta para projetar e analisar circuitos lógicos. 🛠️
- Exemplo de Circuito::A(B+C) é equivalente a AB + AC. 🧮