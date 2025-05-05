# Computer Networks

---

**Tags:** computer-networks3.1

**Que:** Qual camada do modelo OSI fornece comunicação lógica entre processos de aplicação em hosts diferentes?

- [x] Camada de Transporte
- [ ] Camada de Rede
- [ ] Camada de Aplicação
- [ ] Camada Física

**Ans:** Camada de Transporte

---

**Tags:** computer-networks3.1

**Que:** Qual a principal função da camada de transporte?

- [ ] Roteamento de pacotes
- [x] Fornecer serviços de comunicação diretamente aos processos de aplicação
- [ ] Tradução de endereços IP
- [ ] Gerenciamento de enlaces físicos

**Ans:** Fornecer serviços de comunicação diretamente aos processos de aplicação

---

**Tags:** computer-networks3.1

**Que:** Qual a abordagem pedagógica utilizada por Kurose para o estudo da camada de transporte?

- [ ] Focar apenas nos protocolos TCP e UDP
- [ ] Abordar apenas os princípios teóricos
- [x] Alternar entre discussões de princípios da camada de transporte e a prática em protocolos existentes
- [ ] Concentrar-se na implementação física da camada de transporte

**Ans:** Alternar entre discussões de princípios da camada de transporte e a prática em protocolos existentes

---

**Tags:** computer-networks3.1

**Que:** O que significa "comunicação lógica" fornecida pela camada de transporte?

- [ ] Os hosts estão fisicamente conectados
- [x] Do ponto de vista da aplicação, é como se os hosts estivessem diretamente conectados
- [ ] A comunicação é sempre segura e confiável
- [ ] Os dados são transmitidos em tempo real

**Ans:** Do ponto de vista da aplicação, é como se os hosts estivessem diretamente conectados

---

**Tags:** computer-networks3.1

**Que:** Qual a principal preocupação das aplicações ao utilizar a comunicação lógica fornecida pela camada de transporte?

- [ ] Roteamento de pacotes
- [ ] Tipo de enlace físico
- [x] Detalhes da infraestrutura física
- [ ] Largura de banda disponível

**Ans:** Detalhes da infraestrutura física

---

**Tags:** computer-networks3.1

**Que:** Onde os protocolos da camada de transporte são implementados?

- [ ] Roteadores
- [ ] Switches
- [x] Sistemas finais (hosts)
- [ ] Concentradores (hubs)

**Ans:** Sistemas finais (hosts)

---

**Tags:** computer-networks3.1

**Que:** Como são denominados os pacotes da camada de transporte na terminologia da Internet?

- [ ] Datagramas
- [x] Segmentos
- [ ] Pacotes
- [ ] Quadros

**Ans:** Segmentos

---

**Tags:** computer-networks3.1

**Que:** O que acontece com as mensagens da aplicação na camada de transporte do lado remetente?

- [ ] São enviadas diretamente para o destinatário
- [x] São convertidas em pacotes da camada de transporte (segmentos)
- [ ] São criptografadas
- [ ] São comprimidas

**Ans:** São convertidas em pacotes da camada de transporte (segmentos)

---

**Tags:** computer-networks3.1

**Que:** O que os roteadores de rede examinam em um datagrama?

- [x] Campos da camada de rede
- [ ] Campos do segmento de camada de transporte
- [ ] Dados da aplicação
- [ ] Tamanho do pacote

**Ans:** Campos da camada de rede

---

**Tags:** computer-networks3.1

**Que:** No lado destinatário, qual camada processa o segmento de camada de transporte extraído do datagrama?

- [ ] Camada de rede
- [x] Camada de transporte
- [ ] Camada de aplicação
- [ ] Camada física

**Ans:** Camada de transporte

---

**Tags:** computer-networks3.1

**Que:** Quais são os dois principais protocolos de camada de transporte disponíveis na Internet?

- [ ] HTTP e FTP
- [ ] IP e ARP
- [x] TCP e UDP
- [ ] Ethernet e Wi-Fi

**Ans:** TCP e UDP

---

**Tags:** computer-networks3.1

**Que:** O que o desenvolvedor da aplicação escolhe ao criar sockets?

- [ ] Endereço IP
- [ ] Máscara de sub-rede
- [x] UDP ou TCP
- [ ] Tamanho do pacote

**Ans:** UDP ou TCP

---

**Tags:** computer-networks3.1

**Que:** Qual protocolo fornece comunicação lógica entre hosts?

- [ ] TCP
- [x] IP
- [ ] UDP
- [ ] HTTP

**Ans:** IP

---

**Tags:** computer-networks3.1

**Que:** Qual o modelo de serviço do IP?

- [ ] Confiável e orientado a conexão
- [ ] Não confiável e orientado a conexão
- [ ] Confiável e não orientado a conexão
- [x] Melhor esforço (best-effort)

**Ans:** Melhor esforço (best-effort)

---

**Tags:** computer-networks3.1

**Que:** O que significa o IP oferecer um serviço de "melhor esforço"?

- [ ] Garante a entrega de segmentos
- [ ] Garante a entrega ordenada de segmentos
- [ ] Garante a integridade dos dados
- [x] Faz o "melhor esforço" para entregar segmentos, mas não dá garantias

**Ans:** Faz o "melhor esforço" para entregar segmentos, mas não dá garantias

---

**Tags:** computer-networks3.1

**Que:** Qual a responsabilidade fundamental do UDP e do TCP?

- [x] Ampliar o serviço de entrega IP entre dois sistemas finais para um serviço de entrega entre dois processos
- [ ] Garantir a segurança dos dados transmitidos
- [ ] Roteamento eficiente de pacotes
- [ ] Tradução de endereços IP

**Ans:** Ampliar o serviço de entrega IP entre dois sistemas finais para um serviço de entrega entre dois processos

---

**Tags:** computer-networks3.1

**Que:** Como é denominada a ampliação da entrega hospedeiro a hospedeiro para entrega processo a processo?

- [ ] Roteamento
- [x] Multiplexação/Demultiplexação
- [ ] Fragmentação
- [ ] Encapsulamento

**Ans:** Multiplexação/Demultiplexação

---

**Tags:** computer-networks3.1

**Que:** Quais são os dois serviços mínimos de camada de transporte fornecidos pelo UDP e TCP?

- [ ] Controle de fluxo e controle de congestionamento
- [ ] Transferência confiável de dados e criptografia
- [x] Entrega de dados processo a processo e verificação de erros
- [ ] Estabelecimento de conexão e roteamento

**Ans:** Entrega de dados processo a processo e verificação de erros

---

**Tags:** computer-networks3.1

**Que:** Qual serviço adicional é oferecido pelo TCP, além dos serviços mínimos fornecidos pelo UDP?

- [ ] Criptografia
- [x] Transferência confiável de dados
- [ ] Roteamento eficiente
- [ ] Entrega em tempo real

**Ans:** Transferência confiável de dados

---

**Tags:** computer-networks3.1

**Que:** Qual mecanismo o TCP usa para garantir a transferência confiável de dados?

- [ ] Criptografia e autenticação
- [ ] Roteamento e fragmentação
- [x] Controle de fluxo, números de sequência, reconhecimentos e temporizadores
- [ ] Compressão e descompressão

**Ans:** Controle de fluxo, números de sequência, reconhecimentos e temporizadores

---

**Tags:** computer-networks3.1

**Que:** Qual a principal função do controle de congestionamento no TCP?

- [x] Evitar que uma conexão TCP abarrote os enlaces e roteadores com tráfego excessivo
- [ ] Garantir a largura de banda para uma aplicação específica
- [ ] Criptografar os dados transmitidos
- [ ] Priorizar o tráfego de aplicações sensíveis ao tempo

**Ans:** Evitar que uma conexão TCP abarrote os enlaces e roteadores com tráfego excessivo

---

**Tags:** computer-networks3.1

**Que:** Como o TCP regula a taxa de envio de tráfego para a rede?

- [ ] Aumentando a prioridade dos pacotes
- [x] Regulando a taxa com a qual o lado remetente envia tráfego
- [ ] Fragmentando os pacotes em tamanhos menores
- [ ] Criptografando os dados

**Ans:** Regulando a taxa com a qual o lado remetente envia tráfego

---

**Tags:** computer-networks3.1

**Que:** Qual a principal característica do tráfego UDP em relação ao controle de congestionamento?

- [ ] É regulado pelo TCP
- [x] Não é regulado
- [ ] Tem prioridade sobre o tráfego TCP
- [ ] É criptografado

**Ans:** Não é regulado

---

**Tags:** computer-networks3.1

**Que:** Qual o objetivo da multiplexação na camada de transporte?

- [ ] Criptografar os dados
- [x] Reunir dados de diferentes sockets e encapsulá-los para envio
- [ ] Roteamento de pacotes
- [ ] Fragmentação de dados

**Ans:** Reunir dados de diferentes sockets e encapsulá-los para envio

---

**Tags:** computer-networks3.1

**Que:** Qual o objetivo da demultiplexação na camada de transporte?

- [ ] Criptografar os dados
- [ ] Reunir dados de diferentes sockets
- [x] Entregar os dados contidos em um segmento ao socket correto
- [ ] Roteamento de pacotes

**Ans:** Entregar os dados contidos em um segmento ao socket correto

---

**Tags:** computer-networks3.1

**Que:** O que é necessário para a multiplexação na camada de rede?

- [ ] Endereços IP únicos
- [x] Portas com identificadores exclusivos e campos especiais nos segmentos
- [ ] Criptografia de dados
- [ ] Tamanho máximo de segmento

**Ans:** Portas com identificadores exclusivos e campos especiais nos segmentos

---

**Tags:** computer-networks3.1

**Que:** Quais campos especiais nos segmentos indicam a porta para a qual o segmento deve ser entregue?

- [ ] Endereço IP de origem e destino
- [x] Número de porta de origem e número de porta de destino
- [ ] Número de sequência e número de reconhecimento
- [ ] Tamanho do segmento e checksum

**Ans:** Número de porta de origem e número de porta de destino

---

**Tags:** computer-networks3.1

**Que:** Qual a faixa de números de porta?

- [ ] 0 a 1000
- [ ] 1 a 65536
- [x] 0 a 65535
- [ ] 1024 a 65535

**Ans:** 0 a 65535

---

**Tags:** computer-networks3.1

**Que:** O que são os números de porta entre 0 e 1023?

- [ ] Portas dinâmicas
- [ ] Portas efêmeras
- [x] Números de porta bem conhecidos
- [ ] Portas reservadas para o sistema operacional

**Ans:** Números de porta bem conhecidos

---

**Tags:** computer-networks3.1

**Que:** Quem atribui um número de porta a uma nova aplicação?

- [ ] O sistema operacional
- [ ] O protocolo TCP
- [ ] O protocolo IP
- [x] O desenvolvedor da aplicação

**Ans:** O desenvolvedor da aplicação

---

**Tags:** computer-networks3.1

**Que:** Como a identificação se dá na multiplexação/demultiplexação não orientada a conexão (UDP)?

- [ ] Tupla de quatro elementos: “endereço IP origem + porta origem + IP destino + porta destino”
- [x] Tupla: “endereço IP + porta destino”
- [ ] Somente pela porta de destino
- [ ] Somente pelo endereço IP de destino

**Ans:** Tupla: “endereço IP + porta destino”

---

**Tags:** computer-networks3.1

**Que:** Como a identificação se dá na multiplexação/demultiplexação orientada a conexão (TCP)?

- [ ] Tupla: “endereço IP + porta destino”
- [x] Tupla de quatro elementos: “endereço IP origem + porta origem + IP destino + porta destino”
- [ ] Somente pela porta de destino
- [ ] Somente pelo endereço IP de destino

**Ans:** Tupla de quatro elementos: “endereço IP origem + porta origem + IP destino + porta destino”

---

**Tags:** computer-networks3.1

**Que:** Por que a tupla IP + porta é considerada um identificador único?

- [ ] O IP é dinâmico
- [ ] A porta é aleatória
- [x] O IP é único e a porta é única para cada host
- [ ] Existem várias portas associadas ao mesmo IP

**Ans:** O IP é único e a porta é única para cada host

---

**Tags:** computer-networks3.1

**Que:** O que acontece com os segmentos TCP que chegam com endereços IP de origem ou números de porta de origem diferentes?

- [ ] São descartados
- [x] São direcionados para sockets diferentes
- [ ] São combinados em um único segmento
- [ ] São enviados para o mesmo socket

**Ans:** São direcionados para sockets diferentes

---

**Tags:** computer-networks3.1

**Que:** O que é o "socket de entrada" em uma aplicação servidor TCP?

- [ ] Um socket para envio de dados
- [x] Um socket que espera requisições de estabelecimento de conexão
- [ ] Um socket para criptografia de dados
- [ ] Um socket para roteamento

**Ans:** Um socket que espera requisições de estabelecimento de conexão

---

**Tags:** computer-networks3.1

**Que:** O que é uma requisição de estabelecimento de conexão TCP?

- [ ] Um segmento com dados da aplicação
- [ ] Um segmento com informações de roteamento
- [x] Um segmento TCP com um bit especial de estabelecimento de conexão marcado
- [ ] Um segmento UDP

**Ans:** Um segmento TCP com um bit especial de estabelecimento de conexão marcado

---

**Tags:** computer-networks3.1

**Que:** Quais valores são notados pela camada de transporte no servidor ao receber um segmento de requisição de conexão?

- [ ] Número de sequência e número de reconhecimento
- [x] Número da porta de origem, endereço IP de origem, número da porta de destino e seu próprio endereço IP
- [ ] Tamanho do segmento e checksum
- [ ] TTL e tipo de serviço

**Ans:** Número da porta de origem, endereço IP de origem, número da porta de destino e seu próprio endereço IP

---

**Tags:** computer-networks3.1

**Que:** Como o servidor Web distingue os segmentos dos diferentes clientes?

- [ ] Pelo número de sequência
- [x] Pelos endereços IP e números da porta de origem
- [ ] Pelo tamanho do segmento
- [ ] Pelo checksum

**Ans:** Pelos endereços IP e números da porta de origem

---

**Tags:** computer-networks3.1

**Que:** O que acontece com a conexão TCP e o socket se um servidor usar HTTP não persistente?

- [ ] A conexão é mantida aberta e o mesmo socket é usado
- [x] Uma nova conexão TCP e um novo socket são criados e encerrados para cada requisição/resposta
- [ ] A conexão UDP é usada em vez de TCP
- [ ] Os sockets são reutilizados entre diferentes clientes

**Ans:** Uma nova conexão TCP e um novo socket são criados e encerrados para cada requisição/resposta

---

**Tags:** computer-networks3.1

**Que:** Qual a principal função da camada de transporte que deve ser fornecida no mínimo?

- [ ] Criptografia
- [ ] Roteamento
- [x] Multiplexação/Demultiplexação
- [ ] Compressão

**Ans:** Multiplexação/Demultiplexação

---

**Tags:** computer-networks3.1

**Que:** O que o UDP faz além da multiplexação/demultiplexação e verificação de erros simples?

- [ ] Criptografia
- [x] Praticamente nada
- [ ] Controle de congestionamento
- [ ] Transferência confiável de dados

**Ans:** Praticamente nada

---

**Tags:** computer-networks3.1

**Que:** Qual característica do UDP o torna "não orientado para conexão"?

- [ ] Ele criptografa os dados
- [ ] Ele roteia os dados
- [x] Não há apresentação entre as entidades remetente e destinatária antes de enviar um segmento
- [ ] Ele comprime os dados

**Ans:** Não há apresentação entre as entidades remetente e destinatária antes de enviar um segmento

---

**Tags:** computer-networks3.1

**Que:** Qual exemplo de protocolo de camada de aplicação usa o UDP?

- [ ] HTTP
- [ ] FTP
- [ ] SMTP
- [x] DNS

**Ans:** DNS

---

**Tags:** computer-networks3.1

**Que:** Quais as vantagens de usar UDP em vez de TCP?

- [ ] Transferência confiável de dados
- [ ] Controle de congestionamento
- [x] Melhor controle no nível da aplicação, sem estabelecimento de conexão e pequeno overhead
- [ ] Criptografia integrada

**Ans:** Melhor controle no nível da aplicação, sem estabelecimento de conexão e pequeno overhead

---

**Tags:** computer-networks3.1

**Que:** Qual a diferença no overhead de pacote entre TCP e UDP?

- [ ] TCP tem 8 bytes de overhead e UDP tem 20 bytes.
- [x] TCP tem 20 bytes de overhead e UDP tem 8 bytes.
- [ ] Ambos têm 20 bytes de overhead.
- [ ] Ambos têm 8 bytes de overhead.

**Ans:** TCP tem 20 bytes de overhead e UDP tem 8 bytes.

---

**Tags:** computer-networks3.1

**Que:** É possível uma aplicação de transferência confiável de dados que use UDP?

- [ ] Não, o UDP é inerentemente não confiável
- [x] Sim, mas a aplicação deve implementar os mecanismos de confiabilidade
- [ ] Sim, mas requer criptografia adicional
- [ ] Não, apenas o TCP pode fornecer transferência confiável

**Ans:** Sim, mas a aplicação deve implementar os mecanismos de confiabilidade

---

**Tags:** computer-networks3.1

**Que:** Qual a finalidade do checksum no UDP?

- [ ] Criptografar os dados
- [ ] Roteamento de pacotes
- [x] Detectar erros na transmissão
- [ ] Controle de congestionamento

**Ans:** Detectar erros na transmissão

---

**Tags:** computer-networks3.1

**Que:** Como o UDP no lado remetente calcula o checksum?

- [ ] Criptografando os dados
- [ ] Usando um algoritmo de hash
- [x] Realizando o complemento de 1 da soma de todas as palavras de 16 bits do segmento
- [ ] Calculando a diferença entre os bits 0 e 1

**Ans:** Realizando o complemento de 1 da soma de todas as palavras de 16 bits do segmento

---

**Tags:** computer-networks3.1

**Que:** Qual a abstração de serviço fornecida por um protocolo de transferência confiável de dados?

- [ ] Criptografia de ponta a ponta
- [ ] Roteamento eficiente
- [x] Canal confiável através do qual os dados são transferidos sem corrupção, perda ou desordem
- [ ] Compressão de dados

**Ans:** Canal confiável através do qual os dados são transferidos sem corrupção, perda ou desordem

---

**Tags:** computer-networks3.1

**Que:** Qual a responsabilidade de um protocolo de transferência confiável de dados?

- [ ] Criptografar os dados
- [ ] Roteamento eficiente
- [x] Implementar a abstração de serviço de um canal confiável
- [ ] Comprimir os dados

**Ans:** Implementar a abstração de serviço de um canal confiável

---

**Tags:** computer-networks3.1

**Que:** O que significa dizer que o TCP é orientado à conexão?

- [ ] Os dados são transferidos em circuitos físicos dedicados
- [x] Os processos precisam se "apresentar" antes de enviar dados
- [ ] Os dados são criptografados
- [ ] Os dados são roteados de forma eficiente

**Ans:** Os processos precisam se "apresentar" antes de enviar dados

---

**Tags:** computer-networks3.1

**Que:** O que significa "full-duplex" em uma conexão TCP?

- [ ] Apenas um lado pode enviar dados por vez.
- [ ] A conexão é criptografada.
- [x] Os dados podem fluir em ambas as direções simultaneamente.
- [ ] Os dados são enviados em tempo real.

**Ans:** Os dados podem fluir em ambas as direções simultaneamente.

---

**Tags:** computer-networks3.1

**Que:** O que significa dizer que a conexão TCP é sempre ponto a ponto?

- [ ] Os dados são enviados para todos os hosts na rede.
- [ ] A conexão é criptografada de ponta a ponta.
- [x] A conexão é entre um único remetente e um único destinatário.
- [ ] Os dados são enviados em tempo real.

**Ans:** A conexão é entre um único remetente e um único destinatário.

---

**Tags:** computer-networks3.1

**Que:** Quantos segmentos são enviados durante a apresentação de três vias (3-way handshake) para estabelecer uma conexão TCP?

- [ ] Um
- [ ] Dois
- [x] Três
- [ ] Quatro

**Ans:** Três

---

**Tags:** computer-networks3.1

**Que:** O que ocorre depois que uma conexão TCP é estabelecida?

- [ ] Os processos encerram a conexão imediatamente.
- [ ] Os dados são criptografados automaticamente.
- [x] Os processos podem enviar dados um para o outro.
- [ ] Os dados são roteados através de uma VPN.

**Ans:** Os processos podem enviar dados um para o outro.

---

**Tags:** computer-networks3.1

**Que:** O que é o tamanho máximo do segmento (MSS) no TCP?

- [ ] O tamanho máximo do cabeçalho TCP.
- [x] A quantidade máxima de dados que pode ser retirada e colocada em um segmento.
- [ ] O tamanho máximo do endereço IP.
- [ ] O tamanho máximo da janela de recepção.

**Ans:** A quantidade máxima de dados que pode ser retirada e colocada em um segmento.

---

**Tags:** computer-networks3.1

**Que:** Como é geralmente estabelecido o MSS?

- [ ] É definido aleatoriamente a cada conexão.
- [ ] É determinado pelo sistema operacional.
- [x] É determinado pelo tamanho do maior quadro da camada de enlace (MTU).
- [ ] É definido pelo administrador de rede.

**Ans:** É determinado pelo tamanho do maior quadro da camada de enlace (MTU).

---

**Tags:** computer-networks3.1

**Que:** O que acontece com os segmentos TCP após serem formados?

- [ ] São criptografados.
- [x] São encapsulados em datagramas IP.
- [ ] São descartados se o destino estiver congestionado.
- [ ] São comprimidos.

**Ans:** São encapsulados em datagramas IP.

---

**Tags:** computer-networks3.1

**Que:** O que é o buffer de recepção da conexão TCP?

- [ ] Um buffer para criptografia de dados.
- [ ] Um buffer para dados de roteamento.
- [x] Um buffer onde os dados recebidos são colocados.
- [ ] Um buffer onde os dados a serem enviados são colocados.

**Ans:** Um buffer onde os dados recebidos são colocados.

---

**Tags:** computer-networks3.1

**Que:** O que define uma conexão TCP?

- [ ] Apenas o endereço IP de origem e destino.
- [ ] Apenas os números de porta de origem e destino.
- [x] Buffers, variáveis e um socket de conexão em cada host.
- [ ] Roteadores, switches e repetidores.

**Ans:** Buffers, variáveis e um socket de conexão em cada host.

---

**Tags:** computer-networks3.1

**Que:** O que o campo de dados do segmento TCP contém?

- [ ] Informações de roteamento.
- [ ] Informações de criptografia.
- [x] Dados da aplicação.
- [ ] Informações de checksum.

**Ans:** Dados da aplicação.

---

**Tags:** computer-networks3.1

**Que:** Qual a função do campo de janela de recepção de 16 bits no cabeçalho TCP?

- [ ] Indicar o tamanho máximo do segmento.
- [x] Indicar o número de bytes que um destinatário está disposto a aceitar.
- [ ] Indicar o número de sequência do próximo byte esperado.
- [ ] Indicar o tamanho do buffer de envio.

**Ans:** Indicar o número de bytes que um destinatário está disposto a aceitar.

---

**Tags:** computer-networks3.1

**Que:** Quais são os bits usados para estabelecer e encerrar a conexão TCP no campo de flag?

- [ ] ACK, PSH e URG.
- [ ] RST, SYN e ACK.
- [x] RST, SYN e FIN.
- [ ] FIN, PSH e URG.

**Ans:** RST, SYN e FIN.

---

**Tags:** computer-networks3.1

**Que:** Qual a finalidade do campo de número de sequência no cabeçalho do segmento TCP?

- [ ] Identificar o destinatário.
- [ ] Identificar o remetente.
- [x] Numerar os bytes da cadeia de dados transmitidos.
- [ ] Indicar a prioridade do segmento.

**Ans:** Numerar os bytes da cadeia de dados transmitidos.

---

**Tags:** computer-networks3.1

**Que:** Qual a finalidade do campo de número de reconhecimento no cabeçalho do segmento TCP?

- [ ] Indicar a prioridade do segmento.
- [ ] Identificar o remetente.
- [x] Indicar o número de sequência do próximo byte esperado do outro host.
- [ ] Numerar os bytes da cadeia de dados transmitidos.

**Ans:** Indicar o número de sequência do próximo byte esperado do outro host.

---

**Tags:** computer-networks3.1

**Que:** O que significa dizer que o TCP fornece reconhecimentos cumulativos?

- [ ] Cada byte é reconhecido individualmente.
- [x] O TCP reconhece bytes até o primeiro byte faltante na cadeia.
- [ ] Os reconhecimentos são criptografados.
- [ ] Os reconhecimentos são enviados em tempo real.

**Ans:** O TCP reconhece bytes até o primeiro byte faltante na cadeia.

---

**Tags:** computer-networks3.1

**Que:** O que um hospedeiro pode fazer quando recebe segmentos fora de ordem em uma conexão TCP?

- [x] Conservar os bytes fora de ordem e esperar pelos bytes faltantes, usando mecanismos como SACK para otimizar a retransmissão.
- [ ] Descartar os segmentos imediatamente (incomum em implementações modernas).
- [ ] Enviar uma mensagem de erro.
- [ ] Negociar uma nova conexão TCP.

**Ans:** Ambas as opções são possíveis, dependendo da implementação.

---

**Tags:** computer-networks3.1

**Que:** Por que os lados de uma conexão TCP escolhem ao acaso um número de sequência inicial?

- [ ] Para aumentar a segurança.
- [x] Para minimizar a possibilidade de segmentos antigos serem tomados por válidos em conexões posteriores.
- [ ] Para melhorar o desempenho.
- [ ] Para simplificar o roteamento.

**Ans:** Para minimizar a possibilidade de segmentos antigos serem tomados por válidos em conexões posteriores.

---

**Tags:** computer-networks3.1

**Que:** Qual é o conceito de "piggybacking" em segmentos TCP?

- [ ] A técnica de fragmentar segmentos em partes menores.
- [x] Levar o reconhecimento junto com dados em um mesmo segmento.
- [ ] A técnica de comprimir os dados antes de enviar.
- [ ] A técnica de encriptar os dados antes de enviar.

**Ans:** Levar o reconhecimento junto com dados em um mesmo segmento.

---

**Tags:** computer-networks3.1

**Que:** O que é usado para o gerenciamento de temporizadores TCP, conforme recomendado no RFC 6298?

- [ ] Um temporizador individual para cada segmento.
- [ ] Um conjunto de temporizadores de prioridade.
- [x] Um único temporizador de retransmissão.
- [ ] Nenhum temporizador, dependendo da condição da rede.

**Ans:** Um único temporizador de retransmissão.

---

**Tags:** computer-networks3.1

**Que:** Qual é a função do controle de fluxo no TCP?

- [ ] Evitar o congestionamento na rede.
- [x] Evitar que o remetente sobrecarregue o buffer do receptor.
- [ ] Criptografar os dados.
- [ ] Rotear os pacotes de forma eficiente.

**Ans:** Evitar que o remetente sobrecarregue o buffer do receptor.

---

**Tags:** computer-networks3.1

**Que:** O que é rwnd (receive window) no contexto do controle de fluxo TCP?

- [ ] O tamanho máximo do segmento.
- [ ] O tempo de round-trip da rede.
- [x] O espaço livre no buffer de recepção do receptor.
- [ ] O tamanho da janela de congestionamento.

**Ans:** O espaço livre no buffer de recepção do receptor.

---

**Tags:** computer-networks3.1

**Que:** O que acontece quando um servidor recebe uma solicitação de conexão em uma porta inexistente?

- [ ] Ele ignora a solicitação.
- [ ] Ele envia uma mensagem de erro ICMP.
- [x] Ele retorna um segmento com o bit RST (Reset) ativado.
- [ ] Ele envia um pacote UDP de erro.

**Ans:** Ele retorna um segmento com o bit RST (Reset) ativado.

---

**Tags:** computer-networks3.1

**Que:** Qual a diferença fundamental entre controle de fluxo e controle de congestionamento?

- [ ] Não há diferença, ambos fazem a mesma coisa.
- [ ] Controle de fluxo evita sobrecarga do buffer do receptor e controle de congestionamento criptografa os dados.
- [x] Controle de fluxo evita sobrecarga do buffer do receptor e controle de congestionamento evita congestionamento na rede.
- [ ] Controle de fluxo evita congestionamento na rede e controle de congestionamento evita sobrecarga do buffer do receptor.

**Ans:** Controle de fluxo evita sobrecarga do buffer do receptor e controle de congestionamento evita congestionamento na rede.

---

**Tags:** computer-networks3.1

**Que:** Como um remetente TCP limita a taxa pela qual envia tráfego para sua conexão em relação ao controle de congestionamento?

- [ ] Aumentando a prioridade dos pacotes.
- [x] Limitando a taxa como uma função do congestionamento de rede percebido.
- [ ] Fragmentando os pacotes.
- [ ] Criptografando os dados.

**Ans:** Limitando a taxa como uma função do congestionamento de rede percebido.

---

**Tags:** computer-networks3.1

**Que:** Qual variável adicional é usada para controle de congestionamento no TCP?

- [ ] rwnd (receive window)
- [x] cwnd (congestion window)
- [ ] MSS (maximum segment size)
- [ ] RTT (round trip time)

**Ans:** cwnd (congestion window)

---

**Tags:** computer-networks3.1

**Que:** Qual a relação entre cwnd (congestion window) e rwnd (receive window) na taxa de envio do TCP?

- [ ] A taxa é limitada pelo máximo de cwnd e rwnd.
- [x] A taxa é limitada pelo mínimo de cwnd e rwnd.
- [ ] A taxa é a soma de cwnd e rwnd.
- [ ] A taxa é o produto de cwnd e rwnd.

**Ans:** A taxa é limitada pelo mínimo de cwnd e rwnd.

---

**Tags:** computer-networks3.1

**Que:** Qual o objetivo da fase de "partida lenta" (slow start) no controle de congestionamento TCP?

- [ ] Reduzir o congestionamento imediatamente.
- [x] Aumentar a taxa de envio gradualmente no início da conexão.
- [ ] Enviar dados com alta prioridade.
- [ ] Criptografar os dados.

**Ans:** Aumentar a taxa de envio gradualmente no início da conexão.

---

**Tags:** computer-networks3.1

**Que:** O que acontece com o cwnd durante a fase de partida lenta?

- [ ] Diminui exponencialmente.
- [x] Aumenta exponencialmente.
- [ ] Permanece constante.
- [ ] Varia aleatoriamente.

**Ans:** Aumenta exponencialmente.

---

**Tags:** computer-networks3.1

**Que:** O que acontece quando ocorre um evento de perda (possivelmente devido ao congestionamento) durante a transmissão TCP?

- [ ] O cwnd dobra.
- [x] O cwnd é reduzido para 1 MSS e a partida lenta é reiniciada.
- [ ] A conexão é encerrada.
- [ ] O RTT é aumentado.

**Ans:** O cwnd é reduzido para 1 MSS e a partida lenta é reiniciada.

---
