# Computer Networks

---

**Tags:** computer-networks-study-exam-2

**Que:** O que define um socket no contexto de redes de computadores?

- [ ] O endereço IP do host que está executando um processo.
- [x] Um endpoint de comunicação em uma rede, identificado por um par de endereço IP e número de porta.
- [ ] Apenas o número da porta usada por um serviço.
- [ ] O protocolo (TCP ou UDP) utilizado pela aplicação.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** Qual das alternativas descreve *três* diferenças *corretas* entre os protocolos TCP e UDP?

- [ ] Ambos, TCP e UDP, são orientados à conexão e garantem entrega confiável.
- [ ] TCP é sem conexão e mais rápido que UDP, que é orientado à conexão e mais lento.
- [x] TCP é orientado à conexão, confiável e com controle de congestionamento; UDP é sem conexão, não confiável e sem controle de congestionamento.
- [ ] UDP garante entrega em ordem, enquanto TCP não.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** Por que um servidor web usando a porta 80 (como HTTP) pode atender a múltiplos clientes simultaneamente, apesar de usar uma única porta conhecida?

- [ ] O servidor aloca uma nova porta para cada cliente que se conecta, liberando a porta 80 original para cada nova conexão.
- [ ] O HTTP processa as requisições uma de cada vez de forma muito rápida, dando a impressão de simultaneidade.
- [x] O servidor utiliza o processo de demultiplexação, distinguindo as conexões individuais com base na combinação do endereço IP e porta de origem de cada cliente com seu próprio endereço IP e porta (80).
- [ ] É responsabilidade da camada de rede rotear cada conexão para uma instância separada do servidor dentro do host.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** Qual é a principal necessidade da camada de transporte em uma arquitetura de rede em camadas, considerando que a camada de rede já provê comunicação entre hosts?

- [ ] A camada de transporte provê a tradução de nomes de domínio para endereços IP.
- [ ] A camada de rede apenas conecta redes locais, enquanto a de transporte conecta redes globais.
- [x] A camada de transporte provê comunicação lógica entre *processos* de aplicação em hosts diferentes, e não apenas entre hosts, oferecendo serviços como multiplexação/demultiplexação e, opcionalmente, confiabilidade e controle.
- [ ] A camada de transporte garante a entrega física dos pacotes através da rede.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** No contexto da camada de transporte, como se definem multiplexação e demultiplexação?

- [ ] Multiplexação é o roteamento de pacotes na camada de rede, e demultiplexação é a determinação do próximo salto.
- [x] Multiplexação é a capacidade de múltiplos processos de aplicação compartilharem uma única conexão de rede, e demultiplexação é a entrega correta dos segmentos de transporte recebidos para o processo de aplicação de destino.
- [ ] Demultiplexação permite que um único processo de aplicação envie dados para múltiplos destinos simultaneamente.
- [ ] Ambas referem-se à combinação de múltiplos sinais físicos em um único canal de transmissão.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** Como se estabelece uma "conexão" ou sessão em serviços que utilizam UDP versus aqueles que utilizam TCP?

- [x] Serviços UDP não estabelecem uma "conexão" formal; os dados são enviados diretamente sem handshake. Serviços TCP utilizam um handshake de três vias para estabelecer um estado de conexão antes de enviar dados.
- [ ] Ambos, UDP e TCP, utilizam um handshake de três vias para iniciar a comunicação.
- [ ] UDP usa um handshake simplificado de duas vias para performance, enquanto TCP usa um de três vias.
- [ ] Nem UDP nem TCP precisam de estabelecimento de sessão; eles apenas enviam os dados de forma independente.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** Apesar de não oferecer serviços como confiabilidade ou controle de fluxo, por que o protocolo UDP é utilizado por algumas aplicações?

- [ ] UDP oferece criptografia nativa para garantir a segurança dos dados, o que TCP não faz.
- [x] Por ser mais rápido, ter menor sobrecarga de cabeçalho e processamento, e ser adequado para aplicações que não necessitam de entrega confiável, controle de fluxo ou controle de congestionamento (ex: streaming, jogos).
- [ ] UDP lida melhor com congestionamento da rede do que TCP, pois não retransmite pacotes.
- [ ] UDP é obrigatório para todas as aplicações que rodam sobre IP em dispositivos móveis.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** É possível construir uma aplicação que forneça transferência confiável de dados utilizando o protocolo UDP como base?

- [ ] Não, pois a confiabilidade é uma característica exclusiva da camada de transporte provida apenas pelo TCP.
- [ ] Sim, mas apenas modificando o cabeçalho do pacote UDP para incluir campos de sequência e reconhecimento.
- [x] Sim, é possível, implementando mecanismos de confiabilidade (como numeração de sequência, ACKs, timers e retransmissão) na própria camada de aplicação.
- [ ] Não, pois o UDP não suporta numeração de sequência ou ACKs, tornando a confiabilidade impossível.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** Qual das alternativas descreve corretamente o processo de estabelecimento de conexão TCP conhecido como 3-way handshake?

- [ ] O cliente envia dados, o servidor reconhece com um ACK, e a conexão é estabelecida.
- [ ] O cliente envia SYN, o servidor envia ACK, e a conexão é estabelecida.
- [x] Um cliente envia um segmento SYN, o servidor responde com SYN-ACK, e o cliente finaliza com um ACK, estabelecendo a conexão e trocando números de sequência iniciais.
- [ ] É um processo de três passos para fechar uma conexão TCP de forma ordenada.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** No cabeçalho TCP, qual é a função principal dos campos Número de Sequência (Sequence Number) e Número de Reconhecimento (Acknowledgement Number)?

- [ ] O Número de Sequência identifica o pacote, e o Número de Reconhecimento confirma o último pacote recebido.
- [ ] Ambos são usados exclusivamente para determinar o tamanho da janela de controle de fluxo.
- [x] O Número de Sequência indica a posição do primeiro byte de dados do segmento no fluxo de bytes, e o Número de Reconhecimento indica o próximo byte que o remetente do ACK espera receber.
- [ ] O Número de Sequência é aleatório e muda a cada pacote, enquanto o Número de Reconhecimento é fixo durante a conexão.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** Qual alternativa descreve corretamente o objetivo do Controle de Fluxo e do Controle de Congestionamento no TCP?

- [ ] Ambos se referem a como o receptor limita a taxa de envio do remetente para evitar sobrecarga no host de destino.
- [x] Controle de Fluxo evita que um remetente sobrecarregue um receptor lento, enquanto Controle de Congestionamento evita que o remetente sobrecarregue a rede.
- [ ] Controle de Fluxo evita congestionamento na rede, e Controle de Congestionamento garante a ordem dos pacotes.
- [ ] Ambos são mecanismos para retransmitir pacotes perdidos de forma eficiente.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** No contexto do controle de congestionamento TCP, o que caracteriza a fase de Partida Lenta (Slow Start)?

- [ ] Uma fase onde a janela de congestionamento (cwnd) aumenta linearmente após cada RTT (Round Trip Time).
- [x] Uma fase inicial onde a janela de congestionamento (cwnd) começa pequena (tipicamente 1 MSS) e cresce exponencialmente (dobra) para cada ACK recebido, até atingir um limiar ou ocorrer perda.
- [ ] Uma fase onde o remetente envia dados na menor taxa possível independentemente dos ACKs recebidos.
- [ ] O mecanismo para determinar o RTT (Round Trip Time) inicial de uma conexão.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** Qual é a distinção fundamental entre as funções de Repasse (Forwarding) e Roteamento (Routing) em um roteador?

- [ ] Repasse é feito por roteadores, e Roteamento é feito por switches.
- [x] Roteamento é o processo de determinar as melhores rotas ou caminhos através da rede (decisão a nível de rede), enquanto Repasse é a ação de mover um pacote da interface de entrada para a interface de saída apropriada dentro de um roteador (ação local).
- [ ] Roteamento é apenas para redes locais (LANs), e Repasse é para redes globais (WANs).
- [ ] Ambos se referem ao mesmo processo de envio de pacotes pela rede, sendo apenas sinônimos para o mesmo conceito.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** Apesar da comutação de circuitos garantir banda dedicada e atraso constante, por que a arquitetura da Internet utiliza a comutação de pacotes?

- [ ] A comutação de pacotes garante a entrega confiável e em ordem dos dados, o que a comutação de circuitos não faz.
- [ ] A comutação de circuitos exige tabelas de roteamento muito complexas em comparação com a comutação de pacotes.
- [ ] A Internet foi projetada para suportar apenas tráfego de voz, onde comutação de pacotes é superior.
- [x] A comutação de pacotes é mais eficiente para o tráfego de dados "bursty" da Internet, permite melhor compartilhamento dos recursos de rede entre múltiplos usuários e evita o overhead de estabelecimento e liberação de circuito.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** No contexto da camada de rede (como no IP), o que significa o termo "serviço de melhor esforço" (best-effort service)?

- [ ] Garante a entrega de todos os pacotes, mas não a ordem em que chegam.
- [ ] Garante um atraso mínimo para todos os pacotes para aplicações em tempo real.
- [ ] Garante uma banda larga dedicada para cada conexão, desde que haja recursos disponíveis.
- [x] Significa que a rede tenta entregar os pacotes o máximo possível, mas sem qualquer garantia de entrega, ordem de chegada ou atraso mínimo. Pacotes podem ser perdidos, duplicados ou chegar fora de ordem.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** Qual a principal distinção entre o conceito de Circuito Virtual (na camada de rede) e a Conexão TCP (na camada de transporte)?

- [ ] O Circuito Virtual é orientado a pacotes, e a conexão TCP é orientada a circuitos.
- [ ] Ambos estabelecem estado nos roteadores para garantir a ordem dos pacotes.
- [x] O Circuito Virtual requer estabelecimento de estado e reserva de recursos nos roteadores da *camada de rede*, enquanto a conexão TCP estabelece estado apenas nos *hosts* finais, na *camada de transporte*.
- [ ] O Circuito Virtual garante confiabilidade fim-a-fim, enquanto o TCP não.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** No contexto da arquitetura de roteadores, o que causa a formação de filas (buffers) nas interfaces de entrada?

- [ ] Ocorre quando o buffer de saída de uma interface está cheio e bloqueia o fluxo de pacotes.
- [x] Acontece quando os pacotes chegam em uma interface de entrada a uma taxa que excede a velocidade com que o fabric de comutação consegue movê-los para a interface de saída apropriada.
- [ ] É um mecanismo intencional para garantir a ordem de chegada dos pacotes de diferentes fontes.
- [ ] É primariamente causada por roteamento lento, onde o roteador leva muito tempo para encontrar a rota na tabela FIB.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** No contexto da arquitetura de roteadores, o que causa a formação de filas (buffers) nas interfaces de saída?

- [ ] Acontece quando o buffer de entrada de uma interface está cheio.
- [ ] É causada pela fragmentação de pacotes IP, que aumenta o número de pacotes a serem enviados.
- [x] Ocorre quando os pacotes chegam no buffer de saída de uma interface (vindas do fabric de comutação) a uma taxa maior do que a capacidade do link de saída pode transmiti-los.
- [ ] É um mecanismo para descartar pacotes com TTL expirado antes de enviá-los.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** Qual das alternativas descreve corretamente um dos métodos de comutação (switching) interna de pacotes em um roteador moderno?

- [ ] Comutação por Memória: O roteador usa uma rede de interconexão complexa para mover pacotes em paralelo.
- [ ] Comutação por Interconexão: Pacotes são copiados para a memória principal e depois movidos para a fila de saída.
- [ ] Todos os métodos de comutação transferem pacotes diretamente do cabo de entrada para o cabo de saída sem buffering interno.
- [x] Comutação por Barramento: Pacotes são transferidos da interface de entrada para a de saída por um barramento compartilhado, onde apenas um pacote pode atravessar o barramento por vez.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** No contexto de filas em roteadores, o que é o Bloqueio de Cabeça de Fila (Head-of-Line Blocking - HOL blocking)?

- [ ] Um pacote na cabeça de uma fila de saída não consegue ser transmitido porque o link de saída está congestionado.
- [x] Um pacote na cabeça de uma fila de entrada é impedido de ser comutado para sua interface de saída porque outro pacote à frente na *mesma* fila de entrada precisa de uma interface de saída que está ocupada, mesmo que a interface de saída do primeiro pacote esteja livre.
- [ ] Ocorre quando pacotes de diferentes filas de entrada competem pelo mesmo buffer de saída.
- [ ] É um mecanismo para priorizar pacotes de alta precedência, impedindo que pacotes de baixa prioridade sejam processados.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** Por que um roteador pode precisar fragmentar um datagrama IP recebido antes de encaminhá-lo para o próximo link?

- [ ] Devido ao congestionamento na rede, fragmentar ajuda a reduzir o impacto na latência.
- [x] Porque o datagrama recebido é maior do que a Unidade Máxima de Transmissão (MTU) do link da interface de saída para o qual ele será encaminhado.
- [ ] Para garantir que o TTL do datagrama não expire rapidamente.
- [ ] Para melhorar o desempenho da transmissão em links de alta velocidade, dividindo o datagrama em partes menores.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** Qual é a função principal do campo Time To Live (TTL) no cabeçalho IPv4?

- [ ] Indica o tempo total, em segundos ou milissegundos, que o datagrama pode levar para chegar ao destino.
- [ ] É usado para priorizar o tráfego em roteadores congestionados, pacotes com TTL mais alto têm maior prioridade.
- [x] Impede que datagramas circulem indefinidamente na rede devido a loops de roteamento, fazendo com que cada roteador diminua seu valor e descarte o datagrama se o TTL chegar a zero.
- [ ] Ajuda no controle de fluxo entre o remetente e o receptor, indicando a capacidade de buffer do próximo nó.

**Ans:**

---

**Tags:** computer-networks-study-exam-2

**Que:** No cabeçalho IPv4, qual o propósito do campo "Protocolo" (Protocol)?

- [ ] Para especificar a versão do protocolo IP (IPv4 ou IPv6) utilizada no datagrama.
- [ ] Para indicar o endereço IP do próximo roteador (next hop) na rota para o destino.
- [ ] Para informar se o datagrama foi fragmentado e qual o offset do fragmento.
- [x] Para identificar qual protocolo da camada de transporte (como TCP, UDP) ou protocolo da camada superior o datagrama carrega, permitindo que a camada IP no host de destino entregue a carga útil para o processo ou protocolo correto.

**Ans:**

---
