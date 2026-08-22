# Programming Logic Foundations Lab — Currículo Canônico

## Escopo

O *Programming Logic Foundations Lab* visa desenvolver a capacidade de **resolver problemas computacionais por meio de código**, enfatizando o **racicínio algorítmico e a modelagem de soluções** em termos conceituais, independente de qualquer linguagem específica. O foco central é ensinar a pensar e planejar algoritmos passo a passo, traduzindo requisitos de um problema em instruções sequenciais claras, de modo que um computador possa executá-las. Assim, a abordagem é **independente de linguagem**: conceitos como fluxo de controle, estruturas de dados ou abstração funcional são tratados em nível conceitual, sem dependência de sintaxe ou recursos de linguagens específicas. Na prática, usa-se JavaScript apenas como ferramenta de codificação dos exercícios, mas **os fundamentos essenciais** (como variáveis, loops, funções, coleções, etc.) são apresentados em termos gerais, aplicáveis a qualquer linguagem. A importância dessa base é destacada em literatura especializada: ao “traduzir conceitos abstratos em instruções passo a passo” compreensíveis pelo computador, o domínio da lógica de programação permite projetar soluções lógicas para diversos desafios e facilita a adaptação a novas tecnologias. Em outras palavras, independentemente da linguagem usada, “a lógica subjacente permanece consistente”, tornando essa formação fundamental para a atuação profissional em desenvolvimento de software.

## Mapa curricular

| ID | Bloco |
|:---:|---|
| `PL-01` | [Problema e Algoritmo Sequencial](../practice/pl-01-problema-e-algoritmo-sequencial/) |
| `PL-02` | [Dados e Expressões](../practice/pl-02-dados-e-expressoes/) |
| `PL-03` | [Decisões Condicionais](../practice/pl-03-decisoes-condicionais/) |
| `PL-04` | [Estruturas de Repetição (Loops)](../practice/pl-04-estruturas-de-repeticao-loops/) |
| `PL-05` | [Abstração Funcional (Funções)](../practice/pl-05-abstracao-funcional-funcoes/) |
| `PL-06` | [Estruturas de Dados (Sequências/Arrays)](../practice/pl-06-estruturas-de-dados-sequencias-arrays/) |
| `PL-07` | [Estruturas de Dados Compostas (Registros)](../practice/pl-07-estruturas-de-dados-compostas-registros/) |
| `PL-08` | [Teste, Debugging e Qualidade](../practice/pl-08-teste-debugging-e-qualidade/) |

---

# PL-01 — Problema e Algoritmo Sequencial

## Objetivo

Desenvolver a habilidade de interpretar e especificar problemas simples, e desenhar algoritmos lineares para resolvê-los. Neste bloco, o estudante aprende a identificar os requisitos de um problema (entradas, saídas, restrições) e a conceber soluções passo a passo executáveis de forma sequencial. O foco é o raciocínio algorítmico básico, aprendendo a formular instruções ordenadas que, quando seguidas, levam à solução correta do problema. Verifica-se a capacidade de representar essas instruções em pseudocódigo ou fluxogramas simples e de *simular* mentalmente ou no papel sua execução.

## Unidades

### PL-01.01 — Especificação e Decomposição de Problemas

**Objetivo**

Ensinar a interpretar um enunciado de problema, identificando entradas, saídas e restrições, e a decompor tarefas maiores em subproblemas menores e manejáveis.

**Fundamentos**

- **Problema e requisitos:** análise de enunciado, definição de *input*, *output* e critérios de sucesso.
- **Decomposição:** divisão de um problema complexo em partes menores (subtarefa ou etapas).
- **Casos de uso e limites:** identificar cenários típicos e limites (inputs extremos).
- **Modelagem conceitual:** esquematização de fluxos de informações entre entradas e saídas.

**Competências**

- Interpretar problemas descritos em linguagem natural.
- Identificar e diferenciar entradas, saídas e restrições.
- Decompor tarefas complexas em passos lógicos ou subproblemas.
- Formular metas claras para cada subproblema.

**Dependências**

nenhuma (unidade inicial).

### PL-01.02 — Algoritmos Sequenciais e Fluxo de Execução

**Objetivo**

Introduzir o conceito de **algoritmo** como sequência finita de passos para resolver um problema, e praticar a escrita e o rastreamento de algoritmos simples.

**Fundamentos**

- **Algoritmo:** definição e propriedades (finitude, bem definido).
- **Sequência de comandos:** execução estritamente ordenada de instruções.
- **Representação:** pseudocódigo, fluxograma ou linguagem de alto nível de escolha.
- **Fluxo de execução:** ordem de processamento das instruções, princípio do primeiro para último.

**Competências**

- Elaborar pseudocódigo passo a passo para problemas simples (por exemplo, conversões ou cálculos básicos).
- Rastrear manualmente a execução de um algoritmo sequencial, atualizando valores de variáveis.
- Prever o resultado final de um algoritmo dado (tracing).
- Ajustar o algoritmo diante de erros ou comportamentos inesperados identificados no rastreio.

**Dependências**

PL-01.01.

## Checklist

- [ ] Ler um enunciado e distinguir entradas, saídas e restrições do problema.
- [ ] Decompor um problema em partes menores e descrever cada subproblema.
- [ ] Escrever um algoritmo sequencial (pseudocódigo) que detalhe todos os passos para resolver uma tarefa simples.
- [ ] Simular a execução do algoritmo em papel, rastreando variáveis e verificando se o resultado final está correto.

## Validação do bloco

Ao final de PL-01, o estudante deverá ser capaz de interpretar problemas simples, estruturar o pensamento em etapas lógicas e traduzir essas etapas em um algoritmo sequencial coerente (sem ainda usar condições ou loops). O checkpoint subsequente verificará se o aluno consegue, dado um enunciado claro, propor um algoritmo passo a passo que funcione para casos de teste básicos.

---

# PL-02 — Dados e Expressões

## Objetivo

Introduzir os conceitos de **valor** e **variável** como base para representar e manipular dados em um programa, além de explorar expressões aritméticas e lógicas para calcular resultados. Este bloco foca em como armazenar estado (atribuir e atualizar valores em variáveis) e em como formular expressões que combinam valores e operadores para produzir novo valor. O aluno aprende também sobre tipos de dados básicos (numéricos, booleanos, caracteres/texto) e as regras de precedência de operadores ao avaliar expressões. A capacidade desenvolvida é: definir adequadamente variáveis, atualizá-las por atribuição, escrever expressões matemáticas e lógicas corretas, e rastrear seu valor durante a execução.

## Unidades

### PL-02.01 — Valores, Variáveis e Atribuição

**Objetivo**

Ensinar a representar dados por *valores* literais e a armazená-los em *variáveis*, além de usar a operação de atribuição para atualizar o estado de uma variável.

**Fundamentos**

- **Valor literal:** constante numérica, booleano ou texto (ex.: 42, true, "Olá").
- **Variável:** nome simbólico associado a um espaço de memória que guarda um valor.
- **Tipo de dado:** noções de tipos básicos (inteiro, real/decimal, lógico, caractere/string).
- **Atribuição:** operador para armazenar ou atualizar o valor de uma variável.
- **Estado:** conceito de que variáveis guardam o estado do programa, que muda por atribuições.

**Competências**

- Declarar variáveis conceitualmente e relacioná-las a valores iniciais (ex.: identificar que “idade = 20” armazena valor).
- Atualizar o valor de uma variável com novas atribuições (modelagem de mudança de estado).
- Rastrear passo a passo a evolução dos valores armazenados em variáveis ao longo de um algoritmo.
- Escolher tipos adequados para representar cada informação solicitada pelo problema (ex.: “idades” em número inteiro).

**Dependências**

PL-01.02.

### PL-02.02 — Expressões e Operadores

**Objetivo**

Ensinar a construir e avaliar expressões que combinam variáveis, constantes e operadores para produzir resultados. Inclui operações aritméticas e lógicas, e o entendimento da precedência de operadores.

**Fundamentos**

- **Expressões aritméticas:** soma, subtração, multiplicação, divisão (operadores binários).
- **Expressões lógicas e comparações:** operadores de comparação (==, !=, >, <, >=, <=) e operadores booleanos (AND, OR, NOT), produzindo valores booleanos.
- **Precedência e associatividade:** ordem de avaliação quando múltiplos operadores são usados.
- **Expressões compostas:** combinação de operações aritméticas e comparações em uma única expressão.
- **Avaliação de expressões:** como calcular o resultado passo a passo, substituindo valores e operando.

**Competências**

- Escrever expressões aritméticas corretas para cálculos exigidos pelo problema (ex.: média de notas).
- Escrever condições booleanas com comparações e combinações lógicas para serem usadas em decisões.
- Avaliar manualmente expressões, seguindo regras de precedência, prevendo o resultado.
- Utilizar expressões em atribuições e em condições de controle de fluxo (próximo bloco).

**Dependências**

PL-02.01.

## Checklist

- [ ] Reconhecer quais dados de um problema devem ser armazenados em variáveis e atribuir valores iniciais a elas.
- [ ] Calcular expressões numéricas que envolvam variáveis e constantes (seguindo precedência de operadores).
- [ ] Formular expressões booleanas que comparam variáveis (por exemplo, “idade >= 18”).
- [ ] Rastrear o resultado de uma expressão passo a passo, confirmando se corresponde à expectativa.

## Validação do bloco

Ao final de PL-02, o estudante deverá demonstrar a capacidade de traduzir requisitos de cálculo em expressões que combinam variáveis e operadores, e de manter corretamente o estado (valor) das variáveis por meio de atribuições. O checkpoint verificará se, dado um problema simples de cálculo, o aluno pode declarar variáveis adequadas, computar a expressão correspondente e obter o resultado correto ao rastrear o processo.

---

# PL-03 — Decisões Condicionais

## Objetivo

Introduzir as **decisões condicionais** (ramificações) para permitir que o programa tome diferentes caminhos de execução conforme condições verificadas. O bloco ensina a usar expressões booleanas (criada em PL-02) dentro de estruturas *if-else*, de forma a implementar lógica condicional. Isso inclui operadores lógicos (AND, OR, NOT) e relacionais para construir condições complexas. O estudante aprenderá a prever o fluxo de execução em cada cenário, exercitando o pensamento “if isto, senão aquilo” em pseudocódigo. Essa habilidade permite resolver problemas com múltiplas alternativas (como categorizar dados, validar entradas, etc.).

## Unidades

### PL-03.01 — Estruturas Condicionais (if/else)

**Objetivo**

Ensinar a estrutura de decisão *if* (com possibilidades else/elif) para controlar o fluxo de execução com base em condições booleanas.

**Fundamentos**

- **Decisão simples:** `if (condição) então executar bloco`.
- **Decisão composta:** uso de *if–else* para cobrir os dois caminhos possíveis.
- **Encadeamento:** *else if* (ou elif) para múltiplas condições disjuntas.
- **Expressões condicionais:** combinação de comparadores (==, !=, <, >, etc.) e operadores lógicos (&&, ||, !).
- **Fluxo de controle:** como a escolha (verdadeiro/falso) altera o caminho do algoritmo.

**Competências**

- Formular condições que representam requisitos de decisão (ex.: “idade ≥ 18”).
- Construir pseudocódigo com if–else para casos com um ou mais critérios de escolha.
- Rastrear algoritmos condicionais: verificar quais comandos são executados dado um valor de entrada.
- Identificar e tratar *casos-limite* (por exemplo, exatamente na fronteira da condição) para garantir comportamento correto.

**Dependências**

PL-02.

## Checklist

- [ ] Escrever algorítmicamente estruturas *if* e *if-else* para tomar decisões simples.
- [ ] Avaliar mentalmente uma condição booleana e decidir qual ramo (if ou else) será executado.
- [ ] Enumerar e testar cenários diferentes (inclusive limites) para um mesmo algoritmo condicional.
- [ ] Explicar por que um conjunto de condições em *if-else* cobre corretamente todas as possibilidades do problema.

## Validação do bloco

Ao final de PL-03, o estudante deve provar que domina decisões simples: será solicitado um problema com condições alternativas (por exemplo, verificar elegibilidade ou classificar uma entrada em categorias), e ele deverá escrever o pseudocódigo condicional correspondente e testá-lo em casos diversos. O objetivo é confirmar que ele compreende como *if/else* dirige o fluxo de execução e lida com diferentes situações.

---

# PL-04 — Estruturas de Repetição (Loops)

## Objetivo

Ensinar as **estruturas de repetição** (*loops*) para automatizar tarefas iterativas. Este bloco apresenta o conceito de laço de repetição *for* e *while*, permitindo executar um conjunto de instruções múltiplas vezes conforme uma condição. Aborda a importância da condição de parada (terminação) e operações como contagem ou acumulação dentro do loop. Também explora variações como *loop infinito* e as instruções de controle interno (*break/continue* conceitualmente). A habilidade central é formular loops que resolvam problemas de repetição, como percorrer uma coleção de dados ou acumular valores, sem escrever comandos repetitivos manualmente.

## Unidades

### PL-04.01 — Laços de Repetição (*for* e *while*)

**Objetivo**

Apresentar as estruturas de loop mais comuns (*for* e *while*) para executar código repetidamente enquanto uma condição for verdadeira.

**Fundamentos**

- **Loop controlado (for):** repetição com contador ou iterador definido.
- **Loop condicional (while):** repetição baseada em condição boolean a cada iteração.
- **Terminação:** importância de condições que garantam saída do loop.
- **Incrementos:** atualização de variáveis de controle do loop (por exemplo, contador++).
- **Padrões de iteração:** acumulação (somar valores), contagem de ocorrências, busca por elemento, etc.
- **Instruções de quebra:** (conceitual) *break* e *continue* para alterar o fluxo do loop (avançar ou sair cedo).

**Competências**

- Construir loops *for* que percorrem um número conhecido de iterações (ex.: de 1 até N).
- Construir loops *while* para repetir até que uma condição seja satisfeita (ex.: até que o usuário insira um valor válido).
- Rastrear a execução de um loop (atualização de variáveis a cada passo) e prever quando ele termina.
- Usar loops para realizar algoritmos fundamentais: contagem de elementos, soma de valores, busca sequencial em dados.
- Garantir que cada loop termine adequadamente, evitando repetições infinitas.

**Dependências**

PL-03.

## Checklist

- [ ] Escrever pseudocódigo usando *for* e *while* para tarefas repetitivas (contar de 1 a 10, por exemplo).
- [ ] Determinar e explicar quando um loop termina (identificar condição de parada).
- [ ] Utilizar um loop para acumular ou contar valores dentro de um conjunto de dados fictício.
- [ ] Justificar o uso de *for* versus *while* em diferentes cenários de repetição.

## Validação do bloco

Ao final de PL-04, testaremos se o estudante consegue resolver problemas que exigem repetição, como iterar sobre uma sequência de valores. Será exigido um algoritmo que use loop para processar dados (por exemplo, somar números de uma lista ou encontrar o maior valor). Espera-se que ele escolha corretamente *for* ou *while*, controle adequadamente a condição de término e explique o resultado alcançado.

---

# PL-05 — Abstração Funcional (Funções)

## Objetivo

Ensinar a decomposição de problemas por **funções** (ou procedimentos) para estruturar o código de forma modular. O aluno aprenderá a definir funções que recebem parâmetros de entrada e devolvem um resultado ou realizam uma tarefa específica. Discutiremos parâmetros conceituais, valores de retorno e como uma chamada de função cria um novo escopo de variáveis. O objetivo é habilitar o estudante a dividir um problema em sub-rotinas lógicas reutilizáveis, promovendo clareza e reutilização. Além disso, a prática de projetar funções reforça a habilidade de pensar em termos de *“caixa preta”*: focar no que a função deve fazer (interface) em vez de como é implementada internamente (ocultado do resto do programa).

## Unidades

### PL-05.01 — Definição e Uso de Funções

**Objetivo**

Aprender a definir funções (sub-rotinas) para encapsular tarefas específicas e a utilizá-las em algoritmos maiores.

**Fundamentos**

- **Definição de função:** bloco nomeado que realiza uma tarefa, podendo receber parâmetros e retornar valor.
- **Chamada de função:** invocação do nome da função, passando argumentos, e uso do valor retornado.
- **Parâmetros:** variáveis locais dentro da função que recebem cópia de valores dos argumentos (conceito de passagem por valor).
- **Escopo (conceitual):** distinção entre variáveis locais (dentro da função) e globais (estado externo).
- **Retorno de valor:** enviar o resultado final de volta para o ponto de chamada.
- **Desdobramento funcional:** decompor um problema em diversas funções menores para organizar lógica.

**Competências**

- Escrever pseudocódigo de funções claras, com nomes significativos, parâmetros e possíveis valores de retorno.
- Utilizar funções para evitar duplicação de código (reusar sub-rotinas em várias partes do algoritmo).
- Compor um programa principal que chama funções auxiliares para diferentes subtarefas.
- Rastrear a execução de uma função, entendendo como parâmetros recebem valores e como o resultado é usado após a chamada.

**Dependências**

PL-02, PL-03, PL-04.

## Checklist

- [ ] Projetar uma função para realizar um cálculo ou tarefa bem definida (por exemplo, calcular média, verificar condição).
- [ ] Chamar a função a partir de outro código, passando argumentos e recebendo o resultado corretamente.
- [ ] Explicar o papel de cada parâmetro na função e como eles influenciam o resultado.
- [ ] Organizar um algoritmo dividindo-o em funções menores e coordenadas (modularização).

## Validação do bloco

Ao final de PL-05, o estudante deverá demonstrar que sabe usar funções para estruturar um programa. No checkpoint, será pedido um problema para o qual ele deve criar pelo menos uma função auxiliar: por exemplo, extrair uma tarefa repetitiva para uma função. Ele deverá mostrar que entende como os dados fluem (entradas e retornos) entre o programa principal e as funções definidas.

---

# PL-06 — Estruturas de Dados (Sequências/Arrays)

## Objetivo

Introduzir **coleções ordenadas de dados** (arrays ou listas) como modelo conceitual para agrupar múltiplos valores do mesmo tipo. O estudante aprenderá que uma sequência linear permite armazenar valores em posições indexadas (por exemplo, do índice 0 até *n–1*), facilitando o processamento de conjuntos de dados homogêneos. Serão abordados os fundamentos de acesso indexado, iteração sobre coleções e operações básicas como obter comprimento, buscar elementos e atualizar valores em determinado índice. Este bloco amplia as capacidades de armazenamento além de variáveis unitárias, permitindo resolver problemas como manipulação de listas de números ou strings de forma sistemática.

## Unidades

### PL-06.01 — Sequências Ordenadas (Vetores/Arrays)

**Objetivo**

Ensinar o conceito de sequência indexada para representar uma coleção de valores.

**Fundamentos**

- **Sequência/array:** coleção de tamanho fixo (ou pré-definido), onde cada elemento é acessível por um índice numérico.
- **Indexação:** convenção de índices iniciando em 0 (primeiro elemento) até *n–1* (último elemento), caso haja *n* elementos.
- **Operações básicas:** leitura e escrita de elementos em posições específicas, determinar o comprimento da sequência.
- **Iteração sobre sequências:** uso de loops para percorrer elementos (ex.: `for i de 0 até n-1` realiza ação sobre cada elemento).
- **Processamentos comuns:** acumular valores de uma sequência (por exemplo, somar todos), buscar um item, copiar ou modificar valores.

**Competências**

- Projetar a estrutura de dados sequencial necessária para um problema (por exemplo, “lista de temperaturas mensais”).
- Percorrer uma sequência com loop para realizar operações em todos os elementos ou até encontrar algo específico.
- Acessar corretamente elementos por índice e atualizar seus valores (por exemplo, adicionar ou alterar um elemento).
- Explicar como uma sequência organiza dados de forma indexada e como isso facilita o processamento em comparação a várias variáveis individuais.

**Dependências**

PL-02, PL-04.

## Checklist

- [ ] Criar um modelo de dados sequencial (array/lista) para armazenar valores relacionados.
- [ ] Acessar e alterar um elemento específico da sequência pelo seu índice.
- [ ] Utilizar um loop para iterar sobre todos os elementos de uma sequência e executar uma operação (soma, busca, etc.).
- [ ] Justificar situações em que uma sequência é mais adequada que variáveis individuais.

## Validação do bloco

Ao final de PL-06, a competência verificada será a manipulação de coleções de dados homogêneos. O checkpoint envolverá um problema prático (por exemplo, análise de notas em um vetor) em que o aluno deve utilizar um array implícito para armazenar dados e escrever algoritmos com loops para processá-los (somar valores, encontrar máximo, etc.), demostrando o uso correto de índices e iteração.

---

# PL-07 — Estruturas de Dados Compostas (Registros)

## Objetivo

Introduzir **registros (ou objetos simples)** como modelo para agrupar dados heterogêneos relacionados sob um único conceito. Aqui o estudante vê que, além de coleções lineares, é possível representar entidades com múltiplos atributos (campos) de tipos diferentes. Por exemplo, um “registro Cliente” pode ter campos *nome* (texto), *idade* (inteiro), *ativo* (booleano). Este bloco trata do conceito abstrato de registro, acesso e atualização de campos e, conceitualmente, de coleções de registros (que combinam estruturas seqüenciais e registros). O objetivo é desenvolver a capacidade de **modelar dados compostos** relevantes para o domínio do problema, entendendo que um registro é um agrupamento com campos nomeados.

## Unidades

### PL-07.01 — Registros e Campos

**Objetivo**

Ensinar o conceito de registro (estrutura/registro de dados) como conjunto de campos relacionados, cada um contendo valores de tipos possivelmente diferentes.

**Fundamentos**

- **Registro (struct/objeto):** estrutura composta por um conjunto fixo de campos nomeados, cada campo com seu próprio tipo de dado.
- **Campo/atributo:** elemento do registro, identificado por nome (por exemplo, `id`, `nome`, `salario`).
- **Leitura/escrita de campo:** acessar o valor de um campo de um registro e atribuir novo valor a ele.
- **Inicialização de registro:** processo de criar um novo registro atribuindo valores a cada campo.
- **Coleção de registros (conceitual):** combinação de arrays com registros, representando tabelas ou listas de objetos (cada posição contém um registro).

**Competências**

- Definir mentalmente uma estrutura de registro adequada a um problema (escolher campos relevantes).
- Acessar e atualizar campos específicos de um registro em operações simuladas (por exemplo, `cliente.nome = "Ana"`).
- Trabalhar com coleções de registros: iterar sobre uma lista de registros e operar em campos (por exemplo, buscar cliente por ID).
- Explicar a diferença conceitual entre registros (campos heterogêneos) e sequências (elementos homogêneos).

**Dependências**

PL-02, PL-06.

## Checklist

- [ ] Modelar um registro para representar uma entidade com diversos atributos (por exemplo, produto com preço, quantidade, categoria).
- [ ] Acessar campos de um registro e modificar seus valores.
- [ ] Utilizar um loop para processar uma coleção de registros (por exemplo, somar valores de um campo em todos os registros).
- [ ] Descrever situações em que registros facilitam a organização de dados relacionados.

## Validação do bloco

Ao final de PL-07, será exigido um exercício de modelagem e uso de registros: por exemplo, representar alunos com nome, nota e idade, depois iterar sobre a lista desses alunos para calcular estatísticas. O estudante deverá mostrar que pode definir mentalmente os campos necessários, acessar e atualizar campos em problemas concretos, e justificar por que usar registros é apropriado para o caso dado.

---

# PL-08 — Teste, Debugging e Qualidade

## Objetivo

Consolidar hábitos de **verificação e depuração** contínuos durante o desenvolvimento de código. Este bloco enfatiza o uso de testes para validar algoritmos e o raciocínio passo a passo para localizar erros. O estudante aprende a formular *casos de teste* (válidos, inválidos, limites), a comparar resultados esperados e obtidos, e a adotar estratégias de depuração (por exemplo, imprimir estados intermediários, isolar o trecho problemático). Além disso, introduzimos noções intuitivas de comparação entre soluções alternativas: ao testar duas abordagens corretas, o aluno deve saber justificar qual é mais simples, rápida ou elegante no contexto dado. O foco é desenvolver a capacidade de avaliar criticamente e melhorar soluções de código.

## Unidades

### PL-08.01 — Verificação e Casos de Teste

**Objetivo**

Ensinar a validar algoritmos por meio de testes sistemáticos, cobrindo diferentes casos de entrada.

**Fundamentos**

- **Casos de teste:** definição de cenários de entrada e saída esperada, incluindo casos típicos e casos-limite.
- **Comparação resultado esperado x obtido:** verificar se o algoritmo produz a saída correta para cada caso.
- **Cobertura de casos:** garantir que todas as ramas do algoritmo (condicionais e loops) sejam exercitadas por algum teste.
- **Critérios de término:** estabelecer quando o conjunto de testes é suficiente (ex.: cobertura de caminho, resultados representativos).

**Competências**

- Projetar casos de teste claros para um algoritmo dado, incluindo exemplos normais e limites (ex.: número mínimo/máximo, strings vazias, etc.).
- Executar mentalmente (ou em papel) o algoritmo para um caso de teste e rastrear se o resultado bate com o esperado.
- Identificar discrepâncias entre resultado esperado e obtido.
- Sugerir modificações no algoritmo a partir dos testes falhos.

**Dependências**

Todas as unidades anteriores.

### PL-08.02 — Depuração e Comparação de Soluções

**Objetivo**

Ensinar estratégias de *debugging* (rastreamento de erros) e intuição sobre eficiência ao comparar abordagens.

**Fundamentos**

- **Rastreamento de código:** inspeção passo a passo de trechos de código suspeitos (seguindo valores de variáveis).
- **Isolamento de falhas:** dividir o problema para localizar o trecho exato onde o erro ocorre (hipótese e verificação).
- **Correção de bugs:** entender e aplicar correções pontuais no algoritmo.
- **Comparação de estratégias:** considerar criticamente alternativas de solução (por ex., diferentes estruturas de loop ou funções), pensando em clareza ou custo computacional.
- **Eficiência intuitiva:** noções de tempo de execução relativo (por exemplo, loop aninhado vs. simples) e sua influência prática.

**Competências**

- Rastrear um erro lógico passo a passo, identificando a linha ou expressão incorreta.
- Diagnosticar a causa raiz de um erro sem apenas tentar mudanças aleatórias.
- Correlacionar mudanças no código com variações no comportamento observado.
- Comparar duas soluções funcionais para o mesmo problema, pontuando vantagens/limitações (complexidade de raciocínio, número de passos etc.).

**Dependências**

PL-03, PL-04 (para contexto de estrutura de controle), e testes anteriores.

## Checklist

- [ ] Formular e executar casos de teste suficientes para verificar um algoritmo completo.
- [ ] Detectar em qual parte do código está um erro quando o resultado difere do esperado.
- [ ] Corrigir um erro identificado e confirmar a correção com novos testes.
- [ ] Comparar duas soluções corretas de um mesmo problema e justificar qual é mais adequada no contexto (simplicidade, eficiência ou robustez).

## Validação do bloco

Ao final de PL-08, será exigido um exercício integrador que combine vários fundamentos: o aluno receberá um enunciado com requisitos claros e deverá desenvolver um algoritmo completo (utilizando variáveis, decisões, loops, funções e estruturas de dados conforme necessário) **sem código pronto fornecido**. A tarefa de checkpoint requer que ele proponha a própria solução, realize testes detalhados, identifique e corrija possíveis erros e explique as escolhas feitas. O foco é avaliar a competência cumulativa: o estudante deve demonstrar autonomia em resolver problemas completos, justificando e refinando sua implementação.

---

### Navegação

[← Mapa curricular](./README.md) ·
[↑ Programming Logic Foundations Lab](../README.md) ·
[PL-01 — Problema e Algoritmo Sequencial →](../practice/pl-01-problema-e-algoritmo-sequencial/)
