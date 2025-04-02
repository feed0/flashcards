```markdown
# Compiladores

---

**Tags:** compilers2.1

**Que:** Qual das seguintes opções descreve melhor o objetivo da análise léxica em um compilador?

- [x] Converter o código fonte em uma sequência de tokens.
- [ ] Otimizar o código intermediário para melhor desempenho.
- [ ] Verificar a correção gramatical do código fonte.
- [ ] Gerar código de máquina executável a partir do código fonte.

**Ans:** A análise léxica, também conhecida como scanner, é a primeira fase da compilação e tem como principal objetivo dividir o código fonte em unidades léxicas significativas, chamadas tokens.

---

**Tags:** compilers2.1

**Que:**  Qual termo se refere à sequência de caracteres no código fonte que corresponde a uma unidade léxica?

- [ ] Token
- [x] Lexema
- [ ] Padrão
- [ ] Autômato

**Ans:** Um lexema é a sequência de caracteres real no código fonte que corresponde a um token. Por exemplo, em "int x = 5;", "int", "x", "=", e "5" são lexemas.

---

**Tags:** compilers2.1

**Que:** Qual das seguintes ferramentas é primariamente utilizada para definir os padrões dos tokens na análise léxica?

- [ ] Gramáticas Livres de Contexto
- [x] Expressões Regulares
- [ ] Autômatos de Pilha
- [ ] Árvores Sintáticas Abstratas

**Ans:** Expressões regulares são uma notação formal poderosa para descrever padrões em strings. Na análise léxica, elas são usadas para especificar a estrutura dos lexemas que formam os tokens.

---

**Tags:** compilers2.1

**Que:** O que é um Autômato Finito Determinístico (AFD) no contexto da análise léxica?

- [ ] Um modelo teórico usado apenas para descrever linguagens regulares, sem aplicação prática.
- [x] Um modelo computacional que implementa eficientemente um analisador léxico, reconhecendo tokens.
- [ ] Um tipo de gramática que define a sintaxe de linguagens de programação.
- [ ] Uma estrutura de dados utilizada para armazenar informações sobre os símbolos do programa.

**Ans:** Autômatos Finitos Determinísticos (AFDs) são máquinas de estado finitas que, para cada estado e símbolo de entrada, têm uma única transição definida. Eles são ideais para implementar analisadores léxicos eficientes devido à sua natureza determinística e capacidade de reconhecimento de linguagens regulares.

---

**Tags:** compilers2.1

**Que:** Qual operador de expressão regular representa a repetição de zero ou mais ocorrências de um padrão?

- [ ] +
- [ ] ?
- [x] *
- [ ] |

**Ans:** O operador `*` (asterisco) em expressões regulares indica a repetição de zero ou mais vezes do padrão precedente. Por exemplo, `a*` corresponde a "", "a", "aa", "aaa", e assim por diante.

---

**Tags:** compilers2.1

**Que:**  Qual é a função principal da Tabela de Símbolos (TS) em um compilador?

- [ ] Armazenar o código fonte do programa.
- [ ] Otimizar o processo de análise léxica.
- [x] Armazenar informações sobre os identificadores e outros símbolos do programa.
- [ ] Gerenciar a alocação de memória durante a execução do programa.

**Ans:** A Tabela de Símbolos (TS) é uma estrutura de dados essencial em um compilador, utilizada para armazenar e recuperar informações sobre os identificadores (variáveis, funções, etc.), constantes, e outros símbolos encontrados no código fonte.

---

**Tags:** compilers2.1

**Que:**  O que acontece quando a especificação léxica é ambígua e mais de uma regra pode classificar os próximos caracteres da entrada?

- [ ] O compilador gera um erro de compilação e interrompe o processo.
- [ ] O analisador léxico escolhe aleatoriamente uma das regras correspondentes.
- [x] A regra que casa com o maior número de caracteres tem preferência.
- [ ] A regra que foi definida por último na especificação tem preferência.

**Ans:** Para resolver ambiguidades léxicas, a regra do "maior casamento" (longest match) é geralmente aplicada. Isso significa que o analisador léxico escolhe a regra que consome a maior quantidade possível de caracteres da entrada, garantindo a interpretação mais longa e consistente dos lexemas.

---

**Tags:** compilers2.1

**Que:** Qual das seguintes opções NÃO é tipicamente ignorada pelo analisador léxico?

- [ ] Comentários no código fonte
- [x] Palavras-chave da linguagem
- [ ] Espaços em branco entre tokens
- [ ] Quebras de linha para formatação

**Ans:** O analisador léxico é responsável por identificar e classificar as palavras-chave (keywords) da linguagem como tokens específicos (ex: `if`, `while`, `int`). Comentários, espaços em branco e quebras de linha são geralmente ignorados, pois não contribuem para a estrutura lógica do programa em termos de tokens.

---

**Tags:** compilers2.1

**Que:** Em um token representado como um par (nome, valor), qual é a função do "nome"?

- [ ] Armazenar o lexema correspondente no código fonte.
- [x] Indicar a categoria léxica do token (ex: ID, NUM, OPERADOR).
- [ ] Fornecer o valor literal do token (ex: o valor de um número).
- [ ] Determinar a posição do token no código fonte.

**Ans:** No par (nome, valor) de um token, o "nome" (ou tipo) especifica a categoria léxica à qual o token pertence. Por exemplo, "ID" para identificador, "NUM" para número, "OPERADOR" para um operador, etc. O "valor" pode conter informações adicionais, como o nome do identificador ou o valor numérico.

---

**Tags:** compilers2.1

**Que:** Qual é a relação entre Expressões Regulares (ERs) e Autômatos Finitos (AFs) na análise léxica?

- [ ] AFs são usados para especificar os tokens, enquanto ERs são usados para implementar o analisador léxico.
- [x] ERs são usados para especificar os padrões dos tokens, e AFs são usados para implementar o analisador léxico que reconhece esses padrões.
- [ ] ERs e AFs são ambos usados para otimizar o código intermediário, não para análise léxica.
- [ ] ERs e AFs são estruturas de dados usadas para a tabela de símbolos, não para análise léxica.

**Ans:** Expressões Regulares (ERs) são a ferramenta de especificação para definir os padrões léxicos dos tokens. Autômatos Finitos (AFs), particularmente AFDs, são os modelos computacionais usados para implementar eficientemente o analisador léxico, que efetivamente reconhece as strings que correspondem aos padrões definidos pelas ERs.

---