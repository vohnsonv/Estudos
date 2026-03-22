___
Ref.: [[🎓Engenharia de Software (Graduação)]]
___
Aula com Professor: Júlio Magro

Em maio de 1982, a Telebrás instalou no Rio de Janeiro o primeiro sistema de comunicação óptica desenvolvido com tecnologia brasileira.

O sistema incluía:

1. Equipamento multiplex de 480 canais a 34 Mbit/s
2. Terminal de linha óptica para laser (com detector óptico @830 nm)
3. Cabo de fibra óptica para conexão
4. Outros componentes técnicos como tecnologia de emenda por fusão, caixa de emenda e suportes mecânicos
5. Técnicas de medida do cabo, emendas, perda óptica e largura de banda do link

O texto destaca que, embora hoje essa tecnologia seja comum, na década de 1970, quando o programa de comunicação óptica começou, era uma grande novidade no Brasil.

1. Estrutura da fibra óptica:

- Núcleo (parte central)
- Casca (camada intermediária)
- Capa protetora (camada externa)

2. Tipos de transmissão:

- Multimodo: Neste tipo, a luz faz múltiplas reflexões internas totais, seguindo diferentes caminhos (modos) ao longo da fibra
- Monomodo: A luz segue um único caminho reto, sem reflexões, proporcionando uma transmissão mais direta e eficiente

1. Princípio básico: Utiliza luz infravermelha (invisível) que é guiada através de meios com índices de refração levemente diferentes
2. Índice de Refração (IR):

- Definição: razão entre velocidade da luz no vácuo / velocidade da luz na fibra
- Valores aproximados: 300.000 km/s (vácuo) / 200.000 km/s (fibra)
- IR resultante = 1,5
- Exemplo prático: A luz percorre 1000 km de fibra em 5 ms

3. Características técnicas importantes:

- Atenuação: medida em dB/km, calculada pela fórmula dB = 10 x log₁₀(P₁/P₂)
- Dispersão: medida em ps/nm.km, refere-se ao alargamento do sinal

O DWDM (Dense Wavelength Division Multiplexing)  é uma tecnologia que permite transmitir múltiplos sinais ópticos simultaneamente em diferentes comprimentos de onda através da mesma fibra, aumentando significativamente a capacidade de transmissão.

DWDM com seus principais componentes:

1. Nas extremidades:

- Roteadores em ambos os lados
- Conversores de comprimento de onda (λ1)

2. Componentes principais do sistema:

- Multiplexador/Demultiplexador: combina/separa diferentes comprimentos de onda
- Booster: amplificador na saída do transmissor
- Pré-amplificador: amplificador na entrada do receptor
- Amplificadores ópticos de linha: mantêm a força do sinal ao longo do percurso
- Fibra óptica: meio de transmissão

3. Estrutura bidirecional:

- Fluxo de dados em ambas as direções
- Sistema simétrico com componentes espelhados para transmissão e recepção


Rede GPON (Gigabit Passive Optical Network), que é dividida em três partes principais:

1. Central

- OLT (Optical Line Terminal): equipamento central que gerencia a rede
- DIO (Distribuidor Interno Óptico): ponto de distribuição inicial
- Cabo óptico de alimentação: conecta a central à rede de distribuição

2. Rede óptica de distribuição

- Splitter de distribuição: divide o sinal óptico (1:n)
- Cabo óptico de distribuição: leva o sinal até próximo aos clientes
- Conectores e emendas: para conexões e junções da rede
- Splitter de atendimento: divide novamente o sinal para os clientes finais

3. Cliente

- Cabo óptico drop: última conexão até o cliente
- ONU/ONT (Optical Network Unit/Terminal): equipamento no cliente que converte o sinal óptico

Esta é uma rede "passiva" porque usa apenas componentes ópticos passivos (sem alimentação elétrica) entre a central e o cliente, tornando-a mais econômica e confiável

