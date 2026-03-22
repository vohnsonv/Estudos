___
Disciplina.: [[Arquitetura de Computadores]]
___
## <mark style="background: #FFF3A3A6;">Aula</mark>

**1– Sistemas de numeração**

Sistemas de numeração são sistemas para representação de números. Historicamente vários sistemas de numeração foram desenvolvidos de acordo com os avanços das técnicas matemáticas e da própria civilização. Uma das hipóteses de que tenhamos desenvolvido o sistema decimal de numeração está relacionada à contagem com os 10 dedos das mãos.

Na era digital acostumamo-nos a ouvir falar de _bits_ ou _bytes_. Sabemos que **bit** é a menor unidade de informação na memória do computador (0 ou 1, aberto ou fechado, falso ou verdadeiro). Um **byte** corresponde a 8 bits, mas <mark style="background: #ADCCFFA6;">1 byte (8 bits) consegue armazenar um código que corresponde somente a um único número, letra ou símbolo</mark>. A combinação de cadeias de bits é que permite representar diferentes números agrupando-se na forma de bytes.

É importante ter uma boa noção de notação e bases numéricas quando queremos estudar Computação porque isso tem muitos aproveitamentos na área.

**Notação e bases**

A quantidade de algarismos disponíveis num sistema de numeração designa-se de base.

- Decimal (base 10)
    

0, 1, 2, 3, 4, 5, 6, 7, 8, 9

- Binário (base 2)
    

0, 1

- Octal (base 8)
    

0, 1, 2, 3, 4, 5, 6, 7

- Hexadecimal (base 16)
    

0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E , F

O sistema decimal é o sistema comumente utilizado por nós seres humanos e é constituído por dez algarismos: **0,1,2,3,4,5,6,7,8,9.**

Sabemos que no sistema decimal cada algarismo tem um valor posicional, ou seja, cada algarismo tem um peso de acordo com a sua posição na representação de um dado valor.

Por exemplo, o número 237 na base 10 pode ser decomposto em:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667846483688-wX1e7FiLZs.png)

O **sistema binário** é o sistema mais utilizado por máquinas atualmente uma vez que os sistemas digitais trabalham internamente com dois estados (ligado/desligado, verdadeiro/falso, aberto/fechado). O sistema binário utiliza os símbolos: **0, 1**, sendo cada símbolo designado por bit (_binary digi_t). Um equipamento digital é um grande manipulador de 0´s e 1´s.

O **sistema octal** é um sistema de numeração de base 8, isto é, utiliza 8 símbolos (**0, 1, 2, 3, 4, 5, 6, 7**) para a representação de um determinado valor.

O **sistema hexadecimal** é muito utilizado na programação de microprocessadores (espécie de pequeno computador), especialmente nos equipamentos de estudo e sistemas de desenvolvimento.  Utiliza os símbolos: **0, 1, 2, 3, 4, 5, 6, 7, 8, 9** do sistema decimal e ainda as letras **A, B, C, D, E, F**.

**Importante notar as equivalências:** A=10, B=11, C=12, D=13, E=14 e F=15.

**2 – Conversões de base decimal**

**Conversão de decimal para binário**

Basta dividir sucessivamente por 2 o número decimal e guardar os quocientes que vão sendo obtidos, até que o quociente de uma das divisões seja 0.

O resultado é a sequência de baixo para cima de todos os restos obtidos, conforme ilustra a figura em que é apresentado 25 na base 10 que se torna 11001 na base 2.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667846522147-aTpoMDlsQj.png)

A relação entre números decimais e binários é extremamente comum e importante, dada resumidamente pela tabela abaixo para alguns valores:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667846544628-lgxMT64rFz.png)

**Conversão de decimal para octal**

Neste caso o processo de conversão  se dá por divisões sucessivas por 8.

O resultado é a sequência de baixo para cima de todos os restos obtidos, conforme as imagens abaixo em que transformamos o número 217 (decimal) que vira 331 em octal e o número 37 (decimal) que vira 45 (octal)

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667846569206-YQEX53c7Jr.png)

**Conversão de decimal para hexadecimal**

Desta vez o processo se dá por sucessivas divisões por 16, aproveitando-se o resto conforme abaixo.

O número 223(10) corresponde a DF(16) e o número 76(10) corresponde a 4C(16).

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667846589606-9aC978912h.png)

A tabela abaixo apresenta uma série de números em ordem crescente escritos em decimal e a representação dos mesmos na base hexadecimal:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667846611388-ROKc1ydP0x.png)

**3 - Conversões de base binária, octal e hexadecimal**

**Conversão de binário para decimal:**

É apenas resultado da soma do dígito (o ou 1) multiplicado pela base 2 com o expoente de acordo com sua posição, começando do zero a partir da direita.  
Neste caso o número 11001 (base 2) corresponde a 25 (base 10), conforme ilustrado abaixo:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667846627066-uld2py2ZfK.png)

**Conversão de binário para octal:**

Neste caso, os dígitos do número binário são separados em grupos de 3 bits da direita para a esquerda. Cada grupo de 3 bits é um dígito em octal. Ao final, une-se os resultados.

Caso o número de dígitos do número binário não seja múltiplo de 3, completa-se os dígitos à esquerda com zeros (**0**).

Veja o exemplo abaixo para conversão do número 110101 (base binária) para o número 65 (base octal) e o número 11111 (base 2) para 37 (base 8).

**Binário -> hexadecimal**

**Conversão de binário para hexadecimal:**

Separa-se o número binário em grupos de 4 bits, da direita para a esquerda. Em seguida, transforma-se cada grupo de 4 bits em hexadecimal. Ao final, simplesmente une-se os resultados em um só. Caso o número de dígitos do número binário não seja múltiplo de 4, completa-se os dígitos à esquerda com zeros (0).

Veja o exemplo abaixo para conversão do número 01011011 (base 2 ou binária) para o número 5B (base 16 ou hexa) e o número 111101 (base 2) para 3D (base 16):

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667846656930-d9LkrWkxsv.png)

**4 – Conversão de bases**

**Conversão octal para decimal**

Obtida através da soma dos dígitos do número octal multiplicados pela base 8 elevada à posição colunar do dígito, começando em 0 da direita para a esquerda. Observe os exemplos para os números 331 (base 8) e 45 (base 8).

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667846681816-HiZdllAb4M.png)

**Conversão de octal para hexadecimal**

Transforma-se primeiro o octal em binário e em seguida o binário em hexadecimal:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667846711403-0LUjS9x2wh.png)

**Conversão hexadecimal para decimal**

Realizada através da soma dos dígitos hexadecimais multiplicados pela base 16 elevada à posição colunar contando da direita para a esquerda, começando em 0, de forma semelhante à conversão de binários em decimais:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667846735129-ViywDB0xKS.png)

Note que os caracteres que definem os dígitos hexadecimais A, B e C foram substituídos pelos valores equivalentes em decimais 10, 11 e 12 de acordo com a tabela da lição anterior para a realização do cálculo.

**Conversão hexadecimal para binário**

Decompõem-se o número hexadecimal diretamente em binários de 4 dígitos. Os zeros mais à esquerda do resultado binário podem ser omitidos:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667846760350-VMK9KOB6mm.png)

**Conversão hexadecimal para octal**

Transforma-se primeiro o hexadecimal em binário e em seguida o binário em octal:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667846778749-hLGuFypoQZ.png)

**4 – Grandezas e tabela ASCII**

Sempre vale a pena rever a ideia de grandezas e suas nomenclaturas:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667846799154-09X81eGW5C.png)

**Tabela ASCII**

A tabela ASCII representa o equivalente de uma série de símbolos e caracteres presentes em inúmeros programas e aplicações:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667846825669-eG1ZuvLBl6.png)

**Dica**

Um ponto importante a destacar é que existem inúmeras ferramentas de conversão de números entre diferentes bases. Nosso estudo até aqui teve o objetivo de mostrar como é o processo de conversão no sentido de você entender melhor o significado e a importância das bases numéricas. Uma delas é apresentada abaixo ([https://www.cjdinfo.com.br/utilitario-conversor-bases-numericas#:~:text=](https://www.cjdinfo.com.br/utilitario-conversor-bases-numericas%23:~:text=CJDinfo%20-%20Conversor%20de%20Bases%20Num%C3%A9ricas)[CJDinfo%20%2D%20Conversor%20de%20Bases%20Num%C3%A9ricas](https://www.cjdinfo.com.br/utilitario-conversor-bases-numericas%23:~:text=CJDinfo%20-%20Conversor%20de%20Bases%20Num%C3%A9ricas)).

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667846842911-SiMLNn05L5.png)

Referência Bibliográfica

BROOKSHEAR, J.G. **Ciência da** **Computação: uma visão abrangente.** Porto Alegre: Bookman, 2013.

FORBELLONE, A.L.V. & EBERSPACHER, H. F.  **Lógica de Programação –  A Construção de Algoritmos e Estruturas de Dados.** 3ª. Edição. São Paulo, SP: Prentice Hall, 2005.

## <mark style="background: #BBFABBA6;">Resumo</mark>

**O computador entende binário, 8 Bits = 1 Byte = 1 caractere**

**1. Introdução aos Sistemas de Numeração**

- Sistemas de numeração são maneiras de representar números. O sistema decimal (base 10) é o mais comum para humanos, enquanto o binário (base 2) é fundamental para computadores.
- **Bit:** Unidade mínima de informação (0 ou 1).
- **Byte:** 8 bits, que representam um número, letra ou símbolo.

**2. Notação e Bases**

- **Base:** Quantidade de algarismos em um sistema de numeração.
    - Decimal: 0-9
    - Binário: 0-1
    - Octal: 0-7
    - Hexadecimal: 0-9 e A-F (A=10, B=11,... F=15)
- Cada algarismo tem um valor posicional (peso) de acordo com sua posição no número.

**3. Conversões de Base Decimal**

- **Decimal para Binário:** Divisões sucessivas por 2, anotando os restos.
- **Decimal para Octal:** Divisões sucessivas por 8, anotando os restos.
- **Decimal para Hexadecimal:** Divisões sucessivas por 16, anotando os restos.

**4. Conversões de Outras Bases**

- **Binário para Decimal:** Soma dos dígitos multiplicados pela base 2 elevada à sua posição.
- **Binário para Octal:** Agrupar bits em grupos de 3 e converter cada grupo.
- **Binário para Hexadecimal:** Agrupar bits em grupos de 4 e converter cada grupo.
- **Octal para Decimal:** Soma dos dígitos multiplicados pela base 8 elevada à sua posição.
- **Octal para Hexadecimal:** Converter para binário primeiro.
- **Hexadecimal para Decimal:** Soma dos dígitos multiplicados pela base 16 elevada à sua posição.
- **Hexadecimal para Binário:** Converter cada dígito em 4 bits.
- **Hexadecimal para Octal:** Converter para binário primeiro.

**5. Grandezas e Tabela ASCII**

- Revisão das grandezas (kilo, mega, giga, tera, etc.).
- Tabela ASCII: Representação numérica de caracteres e símbolos.

**Dica:** Utilize ferramentas online para conversão entre bases numéricas, como a mencionada no texto original.
## <mark style="background: #FFB86CA6;">Flash Cards</mark>

#flashcards-ArquiteturaDeComputadores
###### Exercícios da Aula

Digitar aqui

###### GEMINI

O que são sistemas de numeração?::Maneiras de representar números, como o decimal e o binário.

O que é um bit?::A menor unidade de informação, que pode ser 0 ou 1.

O que é um byte?::Um conjunto de 8 bits, que representa um número, letra ou símbolo.

O que é a base de um sistema de numeração?::A quantidade de algarismos disponíveis no sistema.

Quais são as bases dos sistemas decimal, binário, octal e hexadecimal?::Decimal: 10, Binário: 2, Octal: 8, Hexadecimal: 16.

Quais são os algarismos do sistema hexadecimal?::0-9 e A-F (A=10, B=11,... F=15).
<!--SR:!2024-10-13,1,230-->

Como converter um número decimal para binário?::Dividir sucessivamente por 2, anotando os restos.

Como converter um número decimal para octal?::Dividir sucessivamente por 8, anotando os restos.

Como converter um número decimal para hexadecimal?::Dividir sucessivamente por 16, anotando os restos.

Como converter um número binário para decimal?::Somar cada dígito multiplicado pela base 2 elevada à sua posição.

Como converter um número binário para octal?::Agrupar os bits em grupos de 3 e converter cada grupo para octal.

Como converter um número binário para hexadecimal?::Agrupar os bits em grupos de 4 e converter cada grupo para hexadecimal.

Como converter um número octal para decimal?::Somar cada dígito multiplicado pela base 8 elevada à sua posição.

Como converter um número octal para hexadecimal?::Converter para binário primeiro.

Como converter um número hexadecimal para decimal?::Somar cada dígito multiplicado pela base 16 elevada à sua posição.

Como converter um número hexadecimal para binário?::Converter cada dígito hexadecimal em um grupo de 4 bits.
<!--SR:!2024-10-13,1,230-->

Como converter um número hexadecimal para octal?::Converter para binário primeiro.

O que é a tabela ASCII?::Uma tabela que representa caracteres e símbolos por números.
## Pensar & Responder

Na especificação de memória de computador, costuma-se utilizar como unidade de medida o Byte e seus múltiplos (KB, MB, GB, TB, PB, etc.), conforme a tabela abaixo:

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1667849404300-zIQT2hDha5.png)

Um funcionário de uma antiga biblioteca de uma pequena cidade do interior pretende digitalizar todo o acervo em papel a fim de preservar aquele valioso acervo e permitir novas formas de aproveitamento do material.

O funcionário pretende se empenhar para digitalizar por meio de reconhecimento de caracteres, não por escaneamento por imagens, que é a forma mais comum. Dessa forma os textos poderão ser estudados por busca por palavras, nomes e cruzamento de expressões, por exemplo.

No acervo, existem cerca de 1000 livros com 150 páginas cada livro, em média.

Considera-se que em uma página de um livro existam aproximadamente 200 palavras, com 7 caracteres cada palavra, também em média.

Considerando que um único BYTE armazena um único caractere (uma letra, número, ou símbolo especial), pergunta-se:

Qual a quantidade aproximada de memória (em MegaByte) o computador que esse funcionário precisará utilizar para armazenar todo o acervo?

Para responder, apresente os cálculos e as hipóteses que julgar necessárias! Além dos cálculos, apresente o resultado em MB, o resultado final deve ser informado no campo texto da resposta, mas anexe um print de uma foto ou arquivo com detalhamento do cálculo que fez.

**RESPOSTA**

Sabendo que 1 Byte representa 1 caractere, devemos achar o total de caracteres do acervo, para encontrarmos o total de Byte necessário e então converter para KB e depois para MB.

  

7 caracteres por palavra

200 palavras por página

150 páginas por livro

1000 possuí o acervo no total

  

Sendo assim, multiplicamos 7x200x150x1000 = 210.000.000 Bytes

  

1 KB = 1024 B

x KB = 210.000.000

  

x = 205.078,125 KB

  

1 MB = 1024 KB

x MB = 205.078,125 KB

  

x = 200,271 MB

  

> Qual a quantidade aproximada de memória (em MegaByte) o computador que esse funcionário precisará utilizar para armazenar todo o acervo?

  

**Resposta: 200 MB**