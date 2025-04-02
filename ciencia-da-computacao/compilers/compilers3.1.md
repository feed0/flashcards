```markdown
# Compilers

---

**Tags:** compilers3.1

**Que:** Qual das seguintes afirmações descreve corretamente o objetivo da análise sintática (parsing) em um compilador?

- [x] Verificar se a sequência de tokens de entrada está de acordo com as regras gramaticais da linguagem e construir uma representação estruturada do programa.
- [ ] Converter o código fonte em linguagem de máquina para execução direta pelo processador.
- [ ] Analisar o significado do programa e garantir que ele execute corretamente semanticamente.
- [ ] Dividir o código fonte em tokens individuais, identificando palavras-chave, operadores e identificadores.

**Ans:** Verificar se a sequência de tokens de entrada está de acordo com as regras gramaticais da linguagem e construir uma representação estruturada do programa.

---

**Tags:** compilers3.1

**Que:** Qual tipo de gramática é mais comumente aceita por algoritmos de análise sintática para realizar o parsing?

- [ ] Gramáticas Irrestritas (Tipo 0)
- [ ] Gramáticas Sensíveis ao Contexto (Tipo 1)
- [x] Gramáticas Livres de Contexto (Tipo 2)
- [ ] Gramáticas Regulares (Tipo 3)

**Ans:** Gramáticas Livres de Contexto (Tipo 2)

---

**Tags:** compilers3.1

**Que:** Qual é a principal diferença entre um analisador sintático descendente (top-down) e um ascendente (bottom-up)?

- [ ] Analisadores descendentes trabalham com gramáticas LR, enquanto ascendentes com gramáticas LL.
- [x] Analisadores descendentes começam com o símbolo inicial da gramática e tentam derivar a entrada, enquanto ascendentes começam com a entrada e tentam reduzir até o símbolo inicial.
- [ ] Analisadores descendentes são mais eficientes em termos de tempo de execução do que os ascendentes.
- [ ] Analisadores descendentes são capazes de lidar com ambiguidades, enquanto ascendentes não.

**Ans:** Analisadores descendentes começam com o símbolo inicial da gramática e tentam derivar a entrada, enquanto ascendentes começam com a entrada e tentam reduzir até o símbolo inicial.

---

**Tags:** compilers3.1

**Que:** O que significa dizer que uma gramática é ambígua?

- [ ] A gramática não consegue gerar nenhuma cadeia de terminais.
- [ ] A gramática gera apenas uma cadeia de terminais.
- [x] Existe pelo menos uma cadeia de terminais que pode ser gerada por mais de uma árvore sintática.
- [ ] A gramática possui recursão à esquerda.

**Ans:** Existe pelo menos uma cadeia de terminais que pode ser gerada por mais de uma árvore sintática.

---

**Tags:** compilers3.1

**Que:** Qual das seguintes opções descreve corretamente um analisador sintático LL(1)?

- [ ] Realiza análise ascendente, utilizando um lookahead de 1 token.
- [x] Realiza análise descendente, utilizando um lookahead de 1 token para tomar decisões de parsing.
- [ ] Realiza análise descendente, sem utilizar lookahead.
- [ ] Realiza análise ascendente, utilizando um lookahead ilimitado.

**Ans:** Realiza análise descendente, utilizando um lookahead de 1 token para tomar decisões de parsing.

---

**Tags:** compilers3.1

**Que:** O que é uma Árvore Sintática Abstrata (AST)?

- [ ] Uma representação linear do código fonte, similar à sequência de tokens.
- [ ] Uma representação detalhada da derivação da string, incluindo todos os passos da análise sintática.
- [x] Uma representação simplificada da estrutura sintática do programa, focada nos aspectos essenciais para as próximas fases do compilador.
- [ ] Uma representação visual da gramática, mostrando as regras de produção e não-terminais.

**Ans:** Uma representação simplificada da estrutura sintática do programa, focada nos aspectos essenciais para as próximas fases do compilador.

---

**Tags:** compilers3.1

**Que:** Qual técnica de parsing é mais simples de implementar a partir de uma gramática, embora possa não funcionar com todas as gramáticas?

- [ ] Analisador LR
- [ ] Analisador SLR
- [ ] Analisador LALR
- [x] Analisador Recursivo

**Ans:** Analisador Recursivo

---

**Tags:** compilers3.1

**Que:** Em um analisador recursivo preditivo, qual é o papel do "lookahead"?

- [ ] Armazenar os tokens já processados para backtracking em caso de erro.
- [ ] Otimizar a velocidade de parsing, pulando tokens irrelevantes.
- [x] Prever qual regra de produção deve ser aplicada em seguida, evitando retrocesso.
- [ ] Indicar o final da entrada de tokens.

**Ans:** Prever qual regra de produção deve ser aplicada em seguida, evitando retrocesso.

---

**Tags:** compilers3.1

**Que:** Qual problema a recursão à esquerda em gramáticas pode causar em analisadores recursivos?

- [ ] Ambiguidade na árvore sintática resultante.
- [ ] Dificuldade na implementação da tabela de parsing.
- [x] Entrada em loop infinito durante o processo de parsing.
- [ ] Incompatibilidade com gramáticas LL(1).

**Ans:** Entrada em loop infinito durante o processo de parsing.

---

**Tags:** compilers3.1

**Que:** Qual é a principal vantagem de utilizar a forma BNF (Backus-Naur Form) ou EBNF (Extended Backus-Naur Form) para especificar a sintaxe de uma linguagem de programação?

- [ ] Permite gerar código de máquina diretamente a partir da especificação.
- [ ] Facilita a análise semântica do código.
- [x] Oferece uma notação formal e concisa para descrever gramáticas livres de contexto.
- [ ] Garante que a gramática resultante seja livre de ambiguidades.

**Ans:** Oferece uma notação formal e concisa para descrever gramáticas livres de contexto.

---