# O que são sistemas digitais?

> Sistemas digitais são definidos como circuitos eletrônicos que empregam a utilização de sinais elétricos em apenas dois níveis de tensão, permitindo sua representação de forma binária. Também são conhecidos como circuitos digitais ou, ainda, circuitos lógicos. Já os impulsos elétricos transportados por esses circuitos são chamados de sinais digitais ou binários.

# Digital vs Analógico

> Os sinais analógicos contêm valores pertencentes a um conjunto contínuo ou infinito de valores, o que se contrapõe aos sistemas digitais, cujos sinais contêm um número finito de valores discretos, normalmente dois.

![](https://senac.blackboard.com/bbcswebdav/pid-9295177-dt-content-rid-238705115_1/institution/Senac%20RS/_cursos_tecnicos/TDS/UC01/conteudos/HTML/01_sistemas_digitais/objetos/fig06.jpg)

# Quantidades digitais

- Sinal binário único é chamado de bit.
- Sinal composto por quatro bits é chamado de nibble.
- Sinal composto por oito bits é chamado de byte.
- Sinal composto por dezesseis bits é chamado de word.

Um sinal digital unico é capaz apenas de representar os valores de verdadeiro ou falso, conjuntos verdadeiro-falso são capazes de representar qualquer ordem de complexidade de um dado problema, daí a importancia das quantidades digitais

![](https://sites.google.com/site/profferdesiqprogaplicccomput/aulas/1-caracterizacao-e-analise-das-formas-de-traducao-de-programas-de-uma-linguagem-de-alto-nivel-para-um-programa-executave)

Em computadores os sinais digitais e suas quantias são normalmente utilizados em multiplos de 8 (do byte para cima)

- 1 byte = 8 bits
- 1 kilobyte (KB) = 1024 bytes
- 1 megabyte (MB) = 1024 kilobytes
- 1 gigabyte (GB) = 1024 megabytes
- 1 terabyte (TB) = 1024 gigabytes
- 1 petabyte (PB) = 1024 terabytes

No geral bits são representações informacionais, isso é, eles carregam determinada informação que em conjunto formam um todo.

# Hardware vs Software

- Hardware: Parte fisica do computador
- Software: Sistemas que definem como deve se comportar o hardware

> Hardware sem um software que o controle é inútil. Todo computador sem software é inútil, pois este, em um computador, não é opcional, já que tudo o que um computador faz desde o momento em que é ligado até o momento em que é desligado é controlado e executado por softwares. A maioria deles pode ser incluída em algumas categorias, as quais você verá em seguida

## Input & Output

> Além disso, um computador não serve para muita coisa se não tiver alguma maneira de o usuário informar dados para serem processados. Para isso, existem dispositivos de entrada e de saída de dados.

- **Dispositivos de entrada** – São todos aqueles cuja interação do usuário direciona a informação para dentro do computador

- **Dispositivos de saída** – São todos aqueles destinados a exibir/receber o resultado do processamento de informações, ou seja, o fluxo é de dentro para fora do computador

- **Dispositivos de entrada/saída** – Existem dispositivos que podem executar operações tanto de entrada quanto de saída. Como exemplo tem-se o pen drive, que pode ser utilizado para receber arquivos contidos no computador e/ou para transportar arquivos para dentro do computador.

# Tipos de Software

> Software é uma coleção de dados, programas, procedimentos, instruções e documentação que executa várias tarefas predefinidas, portanto, conclui-se que é essa coleção que permite a interação entre usuário e computador

## Software de Sistema

> É o software responsável pelo gerenciamento do hardware, ou seja, capaz de gerenciar a comunicação, o comportamento e a interação entre todos os dispositivos de um computador. Pode-se dizer, de uma forma mais simples, que ele é uma camada intermediária entre usuário e máquina.

## Kernel

> O sistema operacional (SO) conta com um subsistema chamado kernel, o núcleo do sistema que conecta o software ao hardware e gerencia a memória e os processos que serão executados

## Gerenciamento de outros softwares

> Além disso, o SO é composto de uma coleção de programas que lida com recursos e fornece serviços gerais para execução de outros aplicativos – é o sistema operacional que permite, por exemplo, a gravação e recuperação de dados da memória secundária, bem como é responsável pela alocação e execução de programas que são colocados na memória principal.

## Drivers de dispositivos

Responsáveis por gerir hardwares especificos, como mouse, teclado, placa de video, adaptadores de rede, etc

## Firmware

> Ainda no contexto de software de sistema, é importante citar o firmware, um software embarcado, ou seja, que vem embutido a um dispositivo normalmente gravado em uma RAM ou em uma Eprom (erasable programmable read-only memory, ou memória programável apagável somente de leitura). O firmware fornece informações essenciais sobre como o dispositivo interage com outro hardware. O exemplo mais clássico é o BIOS (basic input/output system), presente em todos os computadores e notebooks. O firmware é independente do sistema operacional e essencial para iniciar um computador.

# Softwares de aplicação

Como o próprio nome sugere, softwares de aplicação são aqueles que aplicam o sistema, ou seja, se comportam de maneira especifica para solucionar algum problema. Eles funcionam dentro dos sistemas operacionais e executam tarefas das mais diversas, desde calcular uma soma ou imprimir algo na tela, a conectar milhões de usuários através de uma rede social

# Conceitos de rede de computadores

> A integração das comunicações com os computadores influenciou no modo como os computadores eram organizados. O conceito de “centro de computação” como uma sala com um grande computador, em que os colaboradores levavam seu trabalho para processamento, está completamente obsoleto. Isso foi substituído pelas redes de computadores, nas quais o trabalho é realizado em vários computadores separados, mas interligados entre si (TANEMBAUM, 2011).

## Estrutura cliente-servidor

As redes são formadas por computadores autonomos que se comunicam entre sí, a forma mais comum de comunicação entre computadores é a estrutura Cliente-Servidor. Nessa estrutura um computador fornece um tipo de recurso (Servidor) e os demais se conectam a esse computador para utiliza-lo (Cliente)

## Endereço de IP

O endereço de IP é o identificador de um computador na rede

> Em uma rede local, os equipamentos podem se comunicar entre si para compartilhar recursos. Para isso, são necessárias, no mínimo, duas informações importantes: o endereço IP e a máscara de sub-rede. O endereço IP deve ser único para cada computador e a máscara de rede a mesma em todos os equipamentos.
