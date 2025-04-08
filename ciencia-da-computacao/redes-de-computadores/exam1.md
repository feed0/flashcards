# Computer Networks 

---

**Tags:** exam1

**Que:** Qual dos seguintes protocolos é responsável pelo controle de congestionamento na camada de transporte?
- [x] TCP
- [ ] UDP
- [ ] DNS
- [ ] ICMP
- [ ] Todos os protocolos citados executam parte das funções de controle.

**Ans:**

---

**Tags:** exam1

**Que:** Qual a função de um roteador em uma rede?

- [ ] Reduzir a probabilidade de erros entre enlaces.
- [x] Rotear pacotes entre redes diferentes.
- [ ] Gerenciar o acesso à internet.
- [ ] Conectar dispositivos em uma rede local.
- [ ] Todas as alternativas acima.

**Ans:**

---

**Tags:** exam1

**Que:** Qual a função principal de um protocolo de rede.
- [ ] Controlar o acesso à internet.
- [ ] Gerenciar a segurança da rede.
- [ ] Definir o hardware da rede.
- [x] Estabelecer as regras de comunicação entre dispositivos.
- [ ] Nenhuma dessas funções é executava pela camada de rede.

**Ans:**

---

**Tags:** exam1

**Que:** Assinale a alternativa FALSA.
- [ ] UDP, por implementar menos controles, tende a ser mais rápido e menos seguro que TCP.
- [ ] A multiplexação permite que vários sinais compartilhem o mesmo meio de transmissão.
- [ ] O encapsulamemto de dados é o processo de adicionar cabeçalhos e trailers aos pacotes de dados à medida que eles descem pela pilha de protocolos.
- [x] A topologia de rede em estrela é mais vulnerável a falhas do que a topologia em anel.
- [ ] O endereço IP é utilizado para identificar um dispositivo em uma rede local.

**Ans:**

---

**Tags:** exam1

**Que:** Qual tipo de meio de transmissao é mais adequado para longas distancias e alta largura de banda?
- [ ] Satélite de órbita alta/geoestacionários.
- [ ] Par trançado.
- [ ] Cabo coaxial.
- [x] Fibra óptica.
- [ ] Ondas de rádio.

**Ans:**

---

**Tags:** exam1

**Que:** Dadas as afirmativas:

I. O modelo OSI possui 7 camadas, enquanto o modelo TCP/IP possui 5 camadas.
II. A largura de banda de uma rede é medida em bits por segundo (bps).
III. O atraso de processamento em uma rede é causado pela distância física entre os dispositivos.

Assinale a alternativa correta:
- [ ] Todas as alternativas estao corretas.
- [ ] Todas as afirmativas sao falsas.
- [ ] As afirmativas I e II sao falsas.
- [ ] As afirmativas II e III sao falsas.
- [x] Há apenas uma alternativa falsa.

**Ans:**

---

**Tags:** exam1

**Que:** Dadas as afirmativas:

I. A comutacao de pacotes é mais eficiente para transmissao de dados em tempo real do que a comutacao de circuitos.
II. O protocolo TCP garante a entrega confiável de dados, assim como o protocolo UDP.
III. A fibra óptica é um meio de transmissao mais lento do que o cabo coaxial.

Assinale a alternativa correta:

- [ ] Todas as afirmativas estao corretas.
- [x] Todas as afirmativas sao falsas.
- [ ] As afirmativas I e II sao falsas.
- [ ] As afirmativas II e III sao falsas.
- [ ] Há apenas uma alternativa falsa.

**Ans:**

  ---

**Tags:** exam1

**Que:** Dadas as afirmativas:

I. O DNS pode transferir arquivos de dados, embora sem confiabilidade, por usar UDP.
II. Todos os atrasos em uma transmissao sao fixos, pois dependem das condicoes fisicas dos enlaces.

- [ ] Todas as afirmativas estao corretas.
- [ ] Somente a I é falsa.
- [x] Somente a II é falsa.
- [ ] Todas as afiramtivas sao falsas.

**Ans:**

  ---

**Tags:** exam1

**Que:** Conceitue e explique as diferencas entre os atrasos de transmissao e propagacao.

**Ans:** A transmissao de pacotes na camada de enlace comeca e termina no buffer de um roteador apos ser recebido de um dos nós na rede. Pos sua vez, a propagacao comeca na saida de um pacote de um nó ate chegar no proximo nó. A velocidade de transmissao depende do tamanho da fila do buffer, ja a propagacao depende dos meios fisicos dos enlaces.

---

**Tags:** exam1

**Que:** Cite e explique as 5 camadas da pilha TCP/IP

**Ans:** 
Aplicacoes trocam mensagens entre sistemas finais;
Transporte carrega segmentos de dados TCP/UDP;
Rede carrega datagramas com endereco IP;
Enlace carrega quadros entre nós na rede;
Fisica carrega bits pelos meios de transporte.

---

**Tags:** exam1

**Que:** Por que o uso de pilhas de protocolos (modelo de pilha) facilita o funcionamento, disseminacao e o desenvolvimento de aplicacoes?

**Ans:** A pilha ATREF define standards atraves de RFCs pela IETF que proporcionam uma rede robusta com protocolos diferentes para necessidades especificas, como seguranca e confiabilidade. As aplicacoes podem abstrair todas as camadas de rede e estabelecer conexoes entre clientes e servidores sem precisar redefinir protocolos de baixo nivel como os de enlaces. 
