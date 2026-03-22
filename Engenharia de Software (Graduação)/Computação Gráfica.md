___
Disciplina.: [[Arquitetura de Computadores]]
___
## <mark style="background: #FFF3A3A6;">Aula</mark>

**1- Processamento de imagens**

Imagens podem ser captadas por uma variedade de sensores.

O processamento de imagens possibilita inúmeras aplicações tais como transmissão de vídeo, diagnóstico médico, controle de qualidade de processos industriais, vigilância, etc.

Consiste em um conjunto de técnicas para capturar, representar e transformar imagens com o auxílio do computador

O emprego dessas técnicas permite:

– extrair e identificar informações das imagens

– melhorar a qualidade visual

– facilita a percepção humana e a interpretação automática

Dados de entrada e saída são imagens!

• Manipulação dos pontos ou pixels (picture element) da imagem.

• As transformações visam, em geral, melhorar as características visuais da imagem, como aumentar o contraste, foco, reduzir ruídos e distorções.

Interpretação de informações da imagem através de algoritmos computacionais.

• Tomam imagens como entradas, mas produzem outros tipos de saída.

• Obtém parâmetros descritivos da imagem.

• Usada para a realização de Reconhecimento de Padrões, Visão Computacional ou de extração de conhecimento das imagens (Mineração de Imagens).

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201423284-fMlCMi6iog.png)

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201440343-vyflXggxbc.png)

**Processamento de Imagens**

– Entrada: imagem;

– Saída: imagem.

**Síntese de imagens**

– Entrada: representação 3D;

– Saída: imagem.

**Análise de Imagens**

– Entrada: imagem;

– Saída: forma e outras características 3D;

– Exemplos: Visão Computacional, Reconhecimento de padrões.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201469362-nTKnywXyvG.png)

**2 - Forma de Objetos**

Forma e como o objeto interage com a luz.

A forma de um objeto 3D é geralmente descrita com uma coleção de pequenas superfícies planares, chamadas de polígonos ou manchas planas.

Os polígonos são triângulos tem o número mínimo de pontos para representar uma superfície plana.

Dependendo da resolução pretendida, maior o número de polígonos e mais realista será a imagem do objeto.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201491566-zNPziANCGX.png)

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201503984-Uz7zMZexCB.png)

**Forma de Objetos:**

**modelo matemático**

Uma mancha poligonal pode ser obtida de várias formas, uma delas é uma descrição geométrica precisa. Por exemplo, uma esfera é dada por (r é o raio da esfera, x, y, e z são os eixos):

R^2 = x^2 + y^2 = z^2R​2​​=x​2​​+y​2​​=z​2​​

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201525364-4AiKqZlAid.png)

**Forma de Objetos: modelo físico**

Outra forma de construir uma superfície geométrica é por meio da construção de um modelo físico e então localizar pontos em sua superfície tocando os pontos com uma caneta especial ou scanner 3D.

O sistema registra a posição do ponto em um espaço tridimensional.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201544785-hGyhTULG72.png)

**Forma de Objetos: fractais**

Outra técnica é por meio de fractais. Tem sido usado para modelar imagens 3D de montanhas, vegetação, nuvens e até fumaça

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201569063-eNTTQpjzy2.png)

**3 - Superfície de objetos**

Cada vértice de uma mancha poligonal pode incluir informações sobre cores, essa informação pode ser usada na renderização.

Padrões de cores associadas a superfícies, são chamadas de mapeamento de texturas.

A correspondência entre o material real e o digitalizado permite uma variedade incrível de possibilidades.

**Diferentes visualizações: com e sem textura**

**Interface do Bryce para composição  de texturas**

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201593203-OFnuGGOqpe.png)

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201609783-xCDKPDRvmB.png)

**Ajustando uma imagem**

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201631898-iKVrpUYoUy.png)

**Alterando um parâmetro:**

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201651804-BCrv9Bxlb9.png)

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201660966-eqRYev9lz2.png)

**Alterando vários parâmetros:**

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201702546-Gj2rhHZK7A.png)

**Modelando cenas inteiras: 3D Studio**

A montagem de uma cena lembra muito um estúdio físico de verdade.

Contém câmeras, luzes e objetos de cena.

Tudo para contribuir para o realismo da cena.

**4 - Renderização**

**Cenas e objetos**

Uma cena é construída por objetos construídos digitalmente.

A relação entre o grau de detalhe do objeto depende da forma como ele será apresentado.

Quanto mais detalhes, maior o custo que vem associado a trabalho computacional (tempo) e representação de dados (espaço).

Modelos e simulações entre eles começam de forma menos complexa. Quanto mais detalhes, maior o tempo de renderização.

**Renderização 3D**

A renderização em 3D é o processo de computação gráfica em 3D de conversão de modelos 3D em imagens 2D em um computador. As renderizações em 3D podem incluir efeitos fotorrealistas ou estilos não fotorrealistas. Fonte: [https://computer.howstuffworks.com/3dgraphics.htm](https://computer.howstuffworks.com/3dgraphics.htm)

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201759108-aTACADLZ8k.png)

**Reflexão**

Reflexão ou dispersão é a relação entre a iluminação de entrada e de saída em um determinado ponto. As descrições de espalhamento são geralmente fornecidas em termos de uma função de distribuição de espalhamento bidirecional ou BSDF.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201784378-cjAm3YHwhf.png)

**Sombreamento**

O sombreamento aborda como os diferentes tipos de espalhamento são distribuídos pela superfície (ou seja, qual função de espalhamento se aplica onde). Descrições desse tipo são normalmente expressas com um programa chamado shader.

Um exemplo simples de sombreamento é o mapeamento de textura, que usa uma imagem para especificar a cor difusa em cada ponto de uma superfície, fornecendo detalhes mais aparentes.

Algumas técnicas de sombreamento incluem:

**Bump mapping:** Inventado por Jim Blinn, uma técnica de perturbação normal usada para simular superfícies enrugadas.

**Cel shading**: Uma técnica usada para imitar a aparência da animação desenhada à mão.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201807428-23MZfHODfP.png)

**5 - Animação 3D**

**Animação 3D** usa computação gráfica para fazer com que os objetos pareçam se mover no espaço **3D**.

Os artistas usam o software de modelagem **3D** para criar os objetos

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201827508-EC4BFev2Hc.png)

**Morphing: transformação de imagens**

Morphing é um efeito especial em filmes e animações que muda (ou transforma) uma imagem ou forma em outra por meio de uma transição perfeita. Utiliza software de computador para criar transições mais realistas.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201850609-HmGpgYom11.png)

**Dicas**

SketchUp: versão pessoal é gratuita!

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201877430-DwzymSBcZb.png)

**Blender**

O **Blender** é uma multiplataforma gratuita, com ferramentas de modelagem 3D, texturização, composição, renderização, animação e edição de vídeo, o que permite que seja usado para outras funções derivadas da modelagem 3D, como animações e desenvolvimento de jogos.

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201899867-OEvSRFGPzV.png)

**Sugestão: dezenas de efeitos interessantes com o _3dthis.com_**

![](https://paperx-dex-assets.s3.sa-east-1.amazonaws.com/images/1668201925228-9oU3xVf4pU.png)

Referência Bibliográfica

BROOKSHEAR, J.G. **Ciência da Computação**: uma visão abrangente. Porto Alegre: Bookman, 2013.

SOMMERVILLE, I. **Engenharia de Software**. São Paulo: Pearson, 2018.
## <mark style="background: #BBFABBA6;">Resumo</mark>

#### **1. Processamento de Imagens** 🖼️

- Imagens são captadas por sensores e processadas para aplicações como diagnóstico médico, vigilância e transmissão de vídeo.
- O processamento permite:
    - **Melhorar qualidade visual**: aumentar contraste, reduzir ruídos.
    - **Extrair informações**: identificar padrões e realizar reconhecimento automático.
- Tipos:
    - **Entrada e saída como imagens** (manipulação de pixels).
    - **Análise de imagens**: saída com forma e características 3D, como em visão computacional.

---

#### **2. Forma de Objetos** 📐

- **Modelagem com polígonos**: objetos 3D são descritos com pequenos triângulos, permitindo maior realismo com mais polígonos.
- **Modelos matemáticos**: superfícies geométricas como esferas podem ser descritas por equações.
- **Modelos físicos**: scanners 3D capturam pontos de superfícies reais.
- **Fractais**: usados para modelar montanhas, nuvens e fumaça. 🌄

---

#### **3. Superfícies de Objetos** 🌈

- **Texturas**: padrões de cores mapeados em superfícies para realismo.
- **Renderização com texturas**: associar materiais reais a objetos digitais.
- Softwares como **Bryce** permitem criar texturas personalizadas e modelar cenas.

---

#### **4. Renderização** 💡

- Processo de converter modelos 3D em imagens 2D.
- **Complexidade e realismo**: maior detalhamento exige mais tempo de renderização e poder computacional.
- Técnicas:
    - **Reflexão**: relação entre iluminação de entrada e saída.
    - **Sombreamento**: define a distribuição da luz, com ferramentas como shaders.
        - Exemplos:
            - **Bump mapping**: simula superfícies enrugadas.
            - **Cel shading**: imita animações desenhadas à mão. 🎨

---

#### **5. Animação 3D** 🕹️

- Usa gráficos computacionais para criar movimentos realistas no espaço 3D.
- Técnicas:
    - **Morphing**: transforma uma forma em outra com transições suaves.
- Softwares recomendados:
    - **SketchUp**: gratuito para uso pessoal.
    - **Blender**: ferramenta poderosa para modelagem, texturização, animação e edição de vídeo.

---

#### **Dicas e Ferramentas** 🛠️

- **SketchUp**: ótimo para modelagem inicial.
- **Blender**: completo e gratuito para projetos avançados.
- **3dthis.com**: oferece dezenas de efeitos interessantes para experimentação.

---

#### **Conclusão** 🎯

A computação gráfica possibilita desde o processamento e análise de imagens até a criação de cenas realistas e animações. É amplamente usada em setores como entretenimento, engenharia e saúde, com ferramentas acessíveis para iniciantes e profissionais. 🚀
## <mark style="background: #FFB86CA6;">Flash Cards</mark>

#flashcards-ArquiteturaDeComputadores

##### Exercícios da Aula

###### GPT

**Processamento de Imagens::Conjunto de técnicas para capturar, representar e transformar imagens com auxílio do computador. 📷🖥️**

**Manipulação de Pixels::Melhoria de características visuais da imagem, como contraste e redução de ruídos. 🖼️✨**

**Análise de Imagens::Extração de informações descritivas para reconhecimento de padrões ou mineração de imagens. 🔍📊**

**Forma de Objetos::Representação de objetos 3D usando polígonos, como triângulos, para criar superfícies. 📐🔺**

**Modelo Físico::Construção de superfícies geométricas por meio de scanners 3D que capturam pontos reais. 📡🌍**

**Fractais::Técnica para modelar elementos naturais como montanhas e nuvens. 🌄☁️**

**Superfícies de Objetos::Uso de texturas para associar materiais reais aos objetos digitais. 🌈🖌️**

**Renderização::Conversão de modelos 3D em imagens 2D, com efeitos realistas ou estilizados. 💡🎥**

**Reflexão::Relação entre luz incidente e luz refletida em uma superfície. 💡↔️**

**Sombreamento::Definição de distribuição de luz na superfície, utilizando shaders e texturas. 🖤✨**

**Bump Mapping::Técnica para simular superfícies enrugadas, sem alterar a geometria do objeto. 🪨📏**

**Cel Shading::Técnica para dar aparência de animação desenhada à mão. ✍️🎞️**

**Animação 3D::Uso de gráficos computacionais para criar movimentos no espaço tridimensional. 🎭🕹️**

**Morphing::Transformação de uma imagem ou forma em outra por transição suave. 🌟🔄**

**SketchUp::Ferramenta gratuita para modelagem 3D inicial. 🏗️✨**

**Blender::Plataforma completa e gratuita para modelagem, animação e renderização 3D. 🚀🎨**

**3dthis.com::Site com dezenas de efeitos criativos para experimentação em 3D. 🌐🛠️**