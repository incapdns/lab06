# Aproveitando as Tecnologias IoT para um Hospital Inteligente

O artigo em questão tem como tese central o aproveitamento dos recentes avanços das tecnologias IoT (Internet das Coisas) e de redes para desenvolver um ambiente hospitalar completamente integrado, com aparelhos comunicando entre si, compartilhando dados e informações, dando origem ao conceito de um hospital inteligente, ou como escrito pelos autores, um **"smart hospital"**. Os autores exploram ao longo do mesmo diversas tecnologias de comunicação em rede para a troca de informações e dados entre equipamentos médicos, por meio de uma estação centralizada de tratamento de dados, que seria, neste caso, a estação da enfermeira. O conceito aqui proposto pelos autores é de que uma central centralizada de tratamento de dados resultaria em um tratamento mais eficiente aos pacientes, diminuindo infecções hoje presentes no processo hospitalar que muitas vezes podem ter efeitos negativos, podendo até mesmo resultar na perda de um paciente. Vale ressaltar que o escopo dessa rede não se limita ao monitoramento de pacientes, podendo englobar também profissionais médicos e equipamentos. Para a implementação de fato, as tecnologias propostas pelos autores são RFID, WSN e dispositivos móveis inteligentes.

Segue uma breve descrição e contextualização de cada uma destas tecnologias:

## RFID (Identificação por Radiofrequência)

RFID consiste em dispositivos que transmitem dados quando alimentados pelo campo eletromagnético de um leitor. Suas aplicações incluem monitorar objetos e pacientes dentro de um hospital. Trata-se de uma tecnologia de baixo custo e baixo consumo de energia.

## WSN (Rede de Sensores Sem Fio)

WSN consiste em pequenos dispositivos, que comunicam entre si para troca de dados. Embora consumam mais energia do que os RFID, uma rede de WSN tem um alcance de comunicação de até 100 metros ao ar livre. Trata-se de uma tecnologia utilizada para coletar dados ambientais e parâmetros fisiológicos dos pacientes em tempo real.

## Smart Mobile (Dispositivos Móveis Inteligentes)

Smart Mobile consiste na utilização de interfaces como smartphones e tablets, permitindo que médicos e enfermeiros acessem os dados dos pacientes em tempo real. Trata-se de uma tecnologia que faz a ponte direta entre os sensores, seus dados e os profissionais.

Além dessas tecnologias, a ideia seria que elas estariam se comunicando entre si através do protocolo CoAP/IPV6 (Constrained Application Protocol) através de uma rede de comunicação intra-hospitalar sem fio e de baixa potência.
