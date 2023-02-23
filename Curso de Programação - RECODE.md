# Curso de Programação - RECODE 💻

Resumo do curso de Programação ofertado pela RECODE.

# 📌 **Sumário**:

1. Lógica de Programação e Algoritmo;
2. Linguagens de Programação;
3. Ferramentas de Programação Visual;
4. Programando com App Inventor.📲

# 1. Lógica de Programação e Algoritmo:

**Dica**: Fazer exercicios de lógica para desenvolver o raciocínio logico. **Site para praticar Lógica de Programação jogando**: [https://www.geniol.com.br/logica/desafios/basico-1/](https://www.geniol.com.br/logica/desafios/basico-1/)

**Conceito de Lógica de Programação**: É possível dizer que é uma sequência de passos de raciocínio lógico que temos que seguir até encontrar a resposta.

**Conceito de Lógica Booleana**: A lógica booleana incluiu também as negações, as afirmações conjuntas e as  afirmações opcionais. Além da negação **(NÃO/NO)**, as demais postulações da lógica booleana nos trazem os conceitos de afirmações conjuntas **(E/AND)**, e as afirmações opcionais **(OU/OR)**, classificando seus resultados como **VERDADEIRO/TRUE**  ou **FALSO/FALSE.**

![logica booleana.png](https://github.com/jessikahaber/Resumo-de-Cursos-e-Dicas/blob/5859ab791821ad8bac2b18507e02cde26c2b9b78/Curso%20de%20Programa%C3%A7%C3%A3o%20-%20RECODE%20%F0%9F%92%BB%20d8522a8e2214403d9934ae882b94886b/logica_booleana.png)

**Expressões Boleana**: E/AND, OU/OR, NÃO/NO.

**Outras Expressões**: SE/IF, WHILE, FOR, DO, DO WHILE.

**Interpretação**: Mostram como estas expressões em português seriam interpretadas em lógica booleana.

**Atenção**: É recomendado começar o estudo de Algoritmo apenas quando já tiver uma noção bem solida de como usar todas as expressões mencionadas acima.

**Conceito de Algoritmos**: São conjuntos de passos finitos e organizados que, quando executados, resolvem um determinado problema, ou seja, as etapas têm um início e um fim, ou seja, é programação com instruções específicas para o alcance de um determinado objetivo. É uma **“sequência finita de ações executáveis que visam obter uma solução para um determinado tipo de problema”.**

Disposição específica: essa disposição é estruturada e organizada (nome/identificação, ingredientes e modo de preparo).

Estrutura inicial (ingredientes): contém os recursos necessários para que saia conforme o esperado. 

Estrutura principal (modo de preparo): contém instruções que devem ser executadas numa ordem específica e  sequenciada.

# 2. Linguagens de Programação:

**Sistema binário**: O computador é um dispositivo eletrônico e seu funcionamento ocorre por meio de **impulsos elétricos.** Os impulsos elétricos só permitem **2 estágios**: **ligado** e **desligado**. Quando há corrente de impulso, o computador entende como 1 (um), e quando não há corrente de impulso, ele entende como 0 (zero). Logo, o único idioma que o computador entende são as 
****sequências de 0 e 1 , conhecido como sistema binário****.

**Linguagem de máquina**: A **linguagem de máquina** chamada também de **linguagem de baixo nível,** nada mais é do  que a forma de "falar" com o computador por meio do **idioma binário.**  É a maneira pela qual o computador consegue compreender os comandos. Existem muitas outras **linguagens de alto nível** que podemos usar para isso.

1️⃣ **Linguagem Compilada**: Perceba que o hardware fala apenas a linguagem de máquina, portanto, quanto mais alto o nível da linguagem de programação, mais traduções são necessárias para converter os comandos de alto nível em linguagem de máquina. As linguagens compiladas estão ainda presas na arquitetura de hardware do computador, pois, seu funcionamento depende de para qual sistema operacional está sendo compilado (Windows, Linux ou Mac). Por exemplo, a Calculadora do Windows (calc.exe) não funciona em nenhum outro sistema operacional diferente deste, pois foi construída e compilada para a arquitetura da pirâmide da qual faz parte.

![niveis das linguagens.jpg](https://github.com/jessikahaber/Resumo-de-Cursos-e-Dicas/blob/main/Banco%20de%20imagens/Curso%20de%20Programa%C3%A7%C3%A3o%20-%20RECODE/niveis%20das%20linguagens.jpg)

Fonte: Adaptado de Fonte: [www.dsc.ufgc.edu.br](http://www.dsc.ufgc.edu.br/)

Exemplo1: A linguagem **Assembly** está bem próxima da linguagem de máquina, então só precisa de uma **tradução ou transformação**.

Exemplo2: Já as linguagens de alto nível, como o **Fortran** ou **C**, precisam ser **convertidas** para **Assembly,** que depois é novamente convertida em linguagem de máquina.

**Traduções ou Conversões:** são etapas de **transformação** gradual, até chegar ao nível mais baixo de linguagem de máquina. Este processo de transformação é chamado de **compilação**.

**Compilador**: transforma os códigos dos comandos em aplicativos executáveis de conteúdo binário, de baixo nível, para que o computador compreenda e execute o que foi programado. O compilador cria um arquivo contendo códigos binários que podem ser compreendidos e executados.

**Assembly:** é a linguagem que está em um **nível muito baixo**, bem próximo à linguagem de máquina, conforme a figura da pirâmide que vimos. 

**Fortran:** foi a primeira linguagem de programação de **alto nível**, criada em 1954, há quase 70 anos. Até hoje é utilizada em grandes bancos, devido a sua robustez e eficiência.

**C/ C++, COBOL e JAVA**: Estas linguagens podem ser escritas em qualquer editor de texto, mas para transformar seus códigos em um programa de computador é necessário o uso de um compilador.

**VISUAL BASIC, DELPHI, C#**: Estas linguagens, entre outras, precisam de um editor específico e proprietário (do fabricante) para construção de códigos, chamados de IDEs (sigla de Integrated Development Environment, ou Ambiente de Desenvolvimento Integrado).

**IDE** (sigla de Integrated Development Environment, ou Ambiente de Desenvolvimento Integrado): é integrada e responsável pela construção, execução, compilação, testes e etc., sendo tudo no mesmo ambiente.

2️⃣ **Linguagem Interpretada: Algumas linguagens de programação não precisam ser compiladas para funcionar.** Elas estão em um nível tão alto que precisam apenas de outros aplicativos para funcionarem, como um navegador web. Ou seja, o aplicativo pode funcionar em qualquer dispositivo, seja um computador, celular ou TV, sem ter a menor preocupação com o hardware ou o sistema operacional. Estas linguagens são totalmente **independentes**, podendo ser usado qualquer **editor de texto** para construir seus códigos, uma vez que **não precisam de compilação**. **Exemplo**: Escrever no bloco de notas um código em hmtl e executar no navegador de internet.

**Tipos de Linguagens interpretadas**: **JavaScript, PHP, Python** entre outras. Por ser independente da arquitetura de hardware do computador, estas linguagens possuem um nível ainda mais alto.

3️⃣ **Linguagem de Programação Visual:** Algumas plataformas como o **Scratch**, **Blockly**, **Code.org**, entre outras, oferecem um nível de linguagem ainda maior, porém de forma abstrata, realizando a programação de computadores **através de uma linguagem mais visual**.

4️⃣ **Prototipagem:** Na área de **construção de sistemas**, antes de iniciar a **programação de um projeto**, usamos recursos para criar “**plantas**” e “**maquetes**” para  averiguar como o sistema vai ficar, antes de colocar a mão na massa. A criação de protótipos traz muitos pontos positivos, como o ganho de produtividade e agilidade na construção de um projeto. Depois de criado, podemos transformá-lo em um projeto no qual já teremos a estrutura inicial produzida.

**Ferramentas de Prototipagem: Figma; Ionic; Tinkercad.**

**Figma:** O **Figma** é uma ferramenta, dentre muitas outras existentes, para prototipagem de sites web. Com esta ferramenta, você pode: Modificar a estrutura do site, cores, tamanhos, imagens, textos etc.; Criar uma navegabilidade (navegação) entre as telas e simular.; Simular como o site vai se comportar em todos os tipo de telas, tais como computadores, tablets e celulares.; Trabalhar em conjunto com outras pessoas, simultaneamente, no mesmo projeto.

Ao final da prototipação do projeto, você pode exportar o site e terá já construída toda sua estrutura. Agora, com toda esta etapa de construção adiantada, você pode trabalhar apenas na inteligência e programação do site.

**Ionic:** Semelhante ao Figma, o **Ionic** traz elementos para construção de interfaces para smartphones em um mesmo projeto - interface para **Android** e **IOS (iPhone)** - bastando movimentar a chave para escolher qual sistema você quer simular. Além disso, assim como o Figma, você pode exportar a estrutura do projeto e iniciar com a interface gráfica já construída.

**Tinkercad:** Com ela podemos criar protótipos de **projetos de robótica**. Ela permite simular e testar todos os componentes eletrônicos como se fossem reais, inclusive o código e linguagem de programação do projeto. Ao ficar pronto, basta baixar o código e conectar os componentes reais. Esta ferramenta, diferente das anteriores, permite construir e testar todo o projeto. A plataforma também contém projetos abertos de outras pessoas, os quais você pode copiar e aprender mais!

# 3. Ferramentas de Programação Visual:

1️⃣ **Aprendizado Baseado em Comandos:** 

▶️ **Linguagem Logo:** É uma plataforma para ensino e aprendizado de lógica e linguagem de programação. À primeira vista, é bastante simples, mas ela ensina conceitos de comandos, parâmetros e procedimentos, que formam a base do funcionamento de todas as linguagens de programação.

2️⃣ **Aprendizado Baseado em Blocos:** é a construção de algoritmos e lógica de programação por meio da utilização de blocos de montagem. Esses blocos possuem encaixes específicos de acordo com a função e relação entre os conceitos.

****Ferramentas que utilizam o aprendizado em bloco:**** SCRATCH; CODE; BLOCKLY; APP INVENTOR.

▶️ **SCRATCH e CODE**: Possui o objetivo de ensinar lógica de programação de forma mais visual, sem a necessidade de escrita. Em 2013, a organização **Code.org**, criou uma plataforma com a mesma finalidade, lançando “**A Hora do Código**” com atividades voltadas para o ensino de ciência da computação para crianças.

As duas plataformas têm um funcionamento semelhante, usando a temática de games para ensinar a lógica de programação baseada em blocos, onde cada bloco da linguagem possui um comando separado e que podem ser agrupados livremente, caso se encaixem. As ferramentas permitem criar jogos elaborados e a aprender muitos dos conceitos da programação, além de permitir compartilhar e executar o jogo online.

▶️ **BLOCKLY**: É uma biblioteca criada pelo Google, de código aberto, permitindo assim a utilização blocos para construção de diversas atividades, tal qual a criação de gráficos, formulários e diversas outras possibilidades. Diferentemente do **Scratch** e do **Code**, essa ferramenta é mais avançada, pois nos dá a possibilidade de integração com outras tecnologias de programação, permitindo a criação de blocos específicos para cada tipo de projeto.

O **Blockly** permite criar e executar seus algoritmos em formato de blocos e a sua visualização, por exemplo: **visualizar como o código ficaria em diferentes liguagens de programação, como JavaScript, Python, PHP, Lua e Dart,** conforme a imagem abaixo.

O **Blockly** é uma excelente ferramenta para aprendizado sobre o funcionamento e abordagem de diferentes linguagens de programação. Devido ao fato de ser uma biblioteca de código aberto, foi utilizada em diversos projetos para a construção de plataformas como o proprio **Code.org**
 e o **App Inventor.**

▶️ **APP INVENTOR**: Esta plataforma ([https://appinventor.mit.edu/](https://appinventor.mit.edu/)) possui um grande diferencial quando comparado às ferramentas anteriores, já que seu projeto é totalmente voltado para celulares, permitindo assim o desenvolvimento de aplicativos totalmente funcionais, rodando diretamente em celulares ou emuladores.

Uma vez criados no **App Inventor**, esses aplicativos ficam limitados apenas a arquitetura do sistema operacional Android, por outro lado permite a integração com serviços Google e recursos tecnológicos embarcados nesses celulares, tais como:

- Mapas
- Sensores(GPS, Bússola, acelerômetro, etc)
- Armazenamento
- Bluetooth
- Envio de SMS

O **App Inventor**, por trabalhar com código aberto, serviu de base para a criação de outras plataformas concorrentes, como o **Thunkable** e o **Kodular**, que trouxe novas funcionalidades e recursos. As três plataformas voltadas ao desenvolvimento de aplicativos possuem o mesmo formato de funcionamento.

# 4. Programando com App Inventor:

**App Inventor**: É uma aplicação em nuvem, gratuita, onde você pode criar aplicativos para smartphones utilizando a linguagem de programação baseada em blocos. Este tipo de linguagem permite que você pense no problema e consiga resolvê-lo de forma bem simples: arrastando blocos de instruções um após o outro, ao invés de programar utilizando apenas texto de pseudocódigo ou até mesmo usando uma linguagem de programação real e complexa. Leia com atenção **O Guia de Criação de Apps**, no site: [https://www.androidpro.com.br/blog/desenvolvimento-android/app-inventor/](https://www.androidpro.com.br/blog/desenvolvimento-android/app-inventor/)

**Configure o App Inventor**: [https://appinventor.mit.edu/explore/ai2/setup](https://appinventor.mit.edu/explore/ai2/setup)

**Outros tutoriais com Projetos Práticos do App Inventor**: [https://appinventor.mit.edu/explore/ai2/tutorials](https://appinventor.mit.edu/explore/ai2/tutorials)

**Atenção**: Primeiro faça a parte visual e depois a lógica de programação que fará o aplicativo ter inteligência. Estabeleça qual o objetivo principal do seu app.

**Lógica Condicional:** Possui uma estrutura condicional, onde dependendo da decisão, um diferente bloco de instrução é executado. A lógica condicional tem a seguinte **estrutura**: **SE/IF, ENTÃO/THEN, SENÃO/ELSE**. Exemplo: Se a <**condição**> for considerada **verdadeira**, as instruções do primeiro bloco (ENTÃO/**THEN**) serão executadas. Se a <**condição**> for **falsa** (não é verdadeira), as instruções do segundo bloco (SENÃO/**ELSE**) serão executadas.

🔴 **Classificação dos operadores**: 

🔺 • operadores **aritméticos (+ (soma), - (subtração), * (multiplicação), / (divisão)):** o operador aritmético para **efetuar uma** **operação matemática.** Assim como na matemática, na programação os operadores seguem uma ordem de precedência para sua execução. A precedência de execução os operadores aritméticos seguem esta ordem: 

▪ 1º parênteses
▪ 2º potências e raízes
▪ 3º multiplicação e divisão
▪ 4º soma e subtração

🔺 • operadores de **atribuição (=):** São usados para **atribuir um valor à um nome, que chamamos de variável**.

🔺 • operadores **relacionais (=):** Os operadores relacionais servem para **verificar uma relação entre 2 valores.** O operador relacional de igualdade é usado para **realizar uma comparação de igualdade** entre um valor e outro. **Todos os demais operadores relacionais**:

• **Igualdade**: este já conhecemos, seu símbolo é o sinal de igual, uma ou duas vezes **(“=” ou “==”)**.

• **Diferença ou desigualdade**: é o inverso da igualdade. Verifica se um valor não é igual a outro. Seus sinais são os símbolos de maior-menor juntos **(“<>”)** ou uma exclamação-igual **(“!=”)**.

• **Menor**: verifica se um valor é menor que outro. Seu símbolo é o sinal de menor mesmo **(“<”)**.

• **Maior**: verifica se um valor é maior que outro. Seu símbolo é o sinal de maior mesmo **(“>”)**.

• **Menor ou igual**: verifica se um valor é menor ou igual a outro. Seu símbolo é um sinal de menor seguido de uma igualdade **(“<=”)**.

• **Maior ou igual**: verifica se um valor é maior ou igual a outro. Seu símbolo é um sinal de maior seguido de uma igualdade **(“>=”)**.

**Atenção**: Em outras linguagens de programação os operadores de atribuição e igualdade podem sofrer alterações, exemplo: 

| Linguagem de programação | Atribuição | Comparação de igualdade |
| --- | --- | --- |
| Delphi | Salário := 1000 (dois pontos e igual) | Quantidade_Filhos = 0 |
| Java | Salário = 1000 | Quantidade_Filhos == 0 (2 sinais de igual) |
| Shell Script | Salário = 1000 | Quantidade_Filhos eq 0 (eq é sigla de equal, igual em inglês) |

Esta **forma particular** que cada uma usa **para representar seus comandos** é **chamada de sintaxe**.

🔺 • **Operadores Lógicos:** Os operadores lógicos são: E/**AND,** OU/**OR,** VERDADE/**TRUE,** FALSO/**FALSE, e** NÃO/**NOT**. 

Os **operadores lógicos** AND (E) e OR (OU) funcionam para **verificar se uma expressão é verdadeira ou falsa** quando existem mais de uma condição que precisam ser testadas. Quando consideramos a expressão verdadeira, todos os outros resultados possíveis tornam-se falsos.

No **operador AND**, **o resultado** da condição só **é verdadeiro** apenas **se todas as condições são verdadeiras**.

No **operador OR,** o **resultado** da condição **é verdadeiro** **se pelo menos uma das condições seja verdadeira**, ou seja, o operador OR requer que apenas uma das respostas seja verdadeira, e **a expressão** **é falsa apenas quando todas as condições são falsas**.

Podemos executar trechos de códigos se uma condição for VERDADEIRA (TRUE) ou outro trecho de código se a mesma condição for FALSA (FALSE) através da estrutura condicional. O IF sempre busca um valor verdadeiro para executar seu trecho de código contido em THEN, não sendo verdadeiro (valor falso) ele passa para o trecho contido em ELSE.

Estes **operadores TRUE e FALSE** são chamados de **operadores booleanos** e podem funcionar como valores, como se fossem números. 

O funcionamento do **operador NOT** é bem simples, **ele NEGA o conteúdo de um valor booleano**, ou seja, se o valor for TRUE, o NOT o transforma em FALSE e vice-versa. Exemplo: NOT TRUE = FALSE, e NOT FALSE = TRUE.

🔴 **Variáveis e Constantes:**

🔺 **Variáveis**: As variáveis são locais onde **podemos armazenar valores** e, como o nome diz, podem ser alterados ao longo do algoritmo, ou seja, podem ter seus valores variados, podem ter variação. As variáveis têm este nome pois há um outro tipo de armazenamento de valores que **não permitem a mudança de seu valor ao longo do código, são as chamados constantes**.

🔺 **Constantes:** A constante **não permite alterar seu valor depois que definido**, mantendo os valores constantes, conforme seu nome.

1️⃣ **Tipos de dados com o qual podemos trabalhar/armazenar:**

• **Integer (inteiro)**: são os valores numéricos inteiros, sem vírgula decimal, tais como 10, 99, 1000, 9990 etc, assim como valores negativos, como -10, -999 etc.

• **String (texto)**: são os valores compostos por letras ou números, escrito entre aspas, tais como “Roberto”, “Vôo 172”, “Hello World!” etc.

• **Boolean (booleano ou lógico)**: podem assumir apenas 2 valores: TRUE ou FALSE, como já conhecemos.

• **Float (real ou ponto flutuante)**: são os valores numéricos não inteiros, com casas decimais, tais como 10.98, 99.9, 1.0000098 etc, assim como seus valores negativos.

Existem tipos de dados são chamados de **tipos primitivos**, isto significa que seu **funcionamento e uso** **será** exatamente **o mesmo em todas as linguagens de programação**.

2️⃣ **Os valores armazenados nas variáveis podem ser inicializados, atribuídos ou requisitados**:

• **Inicialização (inicialize)**: inicializações são atribuições que **ficam no início do código**. São pré-requisito para o funcionamento do restante do algoritmo.

• **Atribuição (set)**: As atribuições acontecem **sempre que um valor é atribuído à uma variável**.

• **Requisição (get)**: a requisição acontece **sempre que um valor armazenado dentro de uma variável é necessário em outro trecho do código**.

🔴 **Procedimentos (*procedures*):** Os procedimentos ajuda tornando os **códigos menos repetitivos**. As procedures também podem receber valores para sua execução. Esses valores são **variáveis de entrada** e são chamadas de **parâmetros**. podem ser de 2 tipos:

• **Com retorno (return)**: executa um trecho de código e retorna um valor ao terminar. Por exemplo, uma procedure pode ter um código para executar um cálculo e retornar seu resultado.

• **Sem retorno**: apenas executa seu trecho de código. O uso de **procedures sem retorno** é mais simples, pois não possuem retorno (RETURN) e não precisam ser atribuídas (depois) de uma variável.

🔴 **Listas (array** ou **vetores): É um tipo de variável que pode armazenar vários valores**, ou seja, são vários dados em uma mesma variável usando listas. As listas, também são conhecidas como **array** ou **vetores**. **Todos os valores são separados por vírgula e ficam entre colchetes ou parêntesis**. Elas funcionam da seguinte forma: Lista_Funcionários = [“Bruno”, “Luiz”, “Ana”, “João”, “Moisés”]

Para armazenar vários valores numa única variável, **cada item da lista recebe um índice, um número de posição na lista**, sempre **iniciando em zero**. 

**As listas podem ser** de: nomes (strings), valores numéricos ou qualquer outro tipo, como valores mistos, armazenando textos, números, valores booleanos, todos misturados.

**Manipulação**: das listas podem variar, isso porque a **manipulação** de seus dados **pode ser realizada de forma diferenciada de uma linguagem para outra**, mas todas seguem os mesmos **conceitos**.

**Os principais conceitos de manipulação de listas**, são o da **criação**, a **adição** e a **remoção**:

[1] //criação e atribuição
[2] Lista_Funcionários = [“Bruno”, “Luiz”, “Ana”]
[3] 
[4] //adição de novo valor após a criação da lista 
[5] Lista_Funcionários.Add(“Moisés”) 
[6] 
[7] //removendo o segundo item da lista, “Luiz” (2º porque inicia em zero ;-)
[8] Lista_Funcionários.Remove[1]
[9]
[10] //imprime os nomes
[11] print (Lista_Funcionários[0]) //imprime “Bruno”
[12] print (Lista_Funcionários[1]) //imprime “Ana”
[13] print (Lista_Funcionários[2]) //imprime “Moisés”

**Atenção**: Para imprimir um valor, **é preciso usar o seu índice** para ter acesso a cada valor isoladamente. Como vimos, **as listas são armazenadas com um índice**, **sempre iniciando com zero,** isto significa que para saber qual é o último índice, basta lembrar que ele é o índice de número **n-1**, sendo “**n”** a quantidade de itens da lista. Por **exemplo**, numa lista com 400 itens, o número do último índice é 399 (resultado de 400 - 1).

🔴 **Estruturas de Repetição:** 

🔺 **Loops**: Loops significa **ciclo**. Por exemplo: um aparelho de CD, quando você coloca um disco, ele inicia tocando na faixa 1, depois passa para a faixa 2 e assim sucessivamente, até a última faixa do disco. O **ciclo desde a primeira faixa até a última é chamado de loop**.

🔺 **Loop infinito**: **Enquanto não houver uma interrupção no loop, ele nunca vai ter fim**. Exemplo: Se você apertar a tecla “repeat” de seu aparelho de CD, assim que acabar a última música ele reinicia o ciclo e começa a tocar a primeira música do disco novamente. Isto nunca vai ter fim, sempre que chegar ao fim do disco ele volta para o início, por toda a vida.

🔺 **Tipos de estruturas de repetição de Loops:**

1️⃣ **Loop WHILE**: O loop **while** funciona exatamente igual a um CD com repeat, que continua seu ciclo (loop) **enquanto não houver** uma interrupção. **While significa enquanto** em inglês.

Usamos o **loop while** quando **não sabemos** o número de eventos que precisam ser executados ou o número de dados de uma lista.

**Precisa iniciar com uma pergunta** o código para que o loop inicie, afinal, precisa ter uma fila para iniciar o primeiro atendimento. Sem primeiro atendimento, o loop não inicia. Então, **a pergunta precisa ser feita antes e ao final do loop while**. A estrutura de repetição while serve para qualquer necessidade.

**WHILE**: usamos para qualquer situação em que precisamos repetir algo até que uma condição seja satisfeita. Pode ser usada para ler dados de uma lista ou para qualquer outro trecho de código que precisa ser repetido.

2️⃣ **Loop FOR EACH**: O **loop for each, significa para cada**, ele se assemelha muito com o play normal do aparelho de CD que, quando tem um CD de 15 músicas, inicia na primeira música e para na última. E pronto. **O loop for each não precisa de verificação de pergunta no começo e antes do final do loop como o while**. o loop for each funciona apenas para listas, pois ele faz uma iteração para cada um de seus itens.

**FOR EACH**: usamos apenas para iterar (percorrer) itens de uma lista. Pudemos ver sua diferença com o FOR pois, para cada pasta da pilha de nosso exemplo, ele já tem os dados em si mesmo (Funcionário.Tem_Filhos).

3️⃣ **Loop FOR**: O loop FOR é a estrutura de repetição mais organizada das 3 existentes, pois possui uma estrutura mais rígida que precisa ser seguida. **Seu ciclo de repetição é específico e limitado, com conhecimento prévio de quando inicia e quando termina**. 

**FOR**: usamos para percorrer os índices de uma lista ou repetir um trecho de código quando sabemos exatamente a quantidade de vezes que precisam ser repetidas.

O loop FOR precisa ser configurado com 3 informações, e possui o seguinte formato **for (de; até; passo)**. Vamos conhecer cada parte:
• **de**: informação da posição com o qual **índice será iniciado**, ou seja, sua posição inicial.
• **até**: informação da **posição final do** **índice**.
• **passo**: são **os passos que o índice deve percorrer entre o início e o fim**.

Exemplo de uma estrutura desse loop: **FOR (índice = 0; índice < 5; índice = índice + 1)**

Com isso, o loop vai percorrer apenas nessa faixa, parando em 4.

Vamos imaginar 2 situações. Na primeira, eu preciso saber apenas os dados da lista que estão nos índices pares. Para isso, posso simplesmente colocar o passo como índice = índice + 2. Como o índice inicia em zero, o próximo será o índice 2, o seguinte será o índice 4. Só números pares.

A segunda situação é a seguinte: estou com uma empresa com 400 funcionários e todos estão numa lista. Eu preciso fazer uma auditoria nos dados destes funcionários, mas só em alguns. Então, posso programar meu loop for para ter um passo de 10. Assim, vou pegar o funcionário que está na posição 0, depois o funcionário que está na posição 10, o próximo que está na posição 20.

![indice do loop FOR.png](Curso%20de%20Programac%CC%A7a%CC%83o%20-%20RECODE%20%F0%9F%92%BB%20d8522a8e2214403d9934ae882b94886b/indice_do_loop_FOR.png)

O algoritmo FOR para este caso ficaria com a seguinte estrutura:

![loop for estrutura do algoritmo.png](Curso%20de%20Programac%CC%A7a%CC%83o%20-%20RECODE%20%F0%9F%92%BB%20d8522a8e2214403d9934ae882b94886b/loop_for_estrutura_do_algoritmo.png)

**As listas possuem um índice numérico e ordenado iniciando sempre em zero.  Os dicionários (dictionary) são listas onde seu índice pode ser identificado por texto ou número, que é conhecido como chave (key).**

Quando usamos dicionários, as chaves e os valores andam sempre juntos, pois, como podemos perceber, um depende do outro para ter sentido. Eles andam sempre em pares, por isso seus itens são chamados **par chave-valor.**