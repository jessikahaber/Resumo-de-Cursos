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

**Conceito de Lógica Booleana**: A lógica booleana incluiu também as negações, as afirmações conjuntas e as  afirmações opcionais. Além da negação **(NÃO/NO)**, as demais postulações da lógica booleana nos trazem os conceitos de afirmações conjuntas **(E/AND)**, e as afirmações opcionais **(OU/OR)**, ****classificando seus resultados como **VERDADEIRO/TRUE**  ou **FALSO/FALSE.**

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

****Ferramentas de Prototipagem: Figma; Ionic**

****Figma:** O **Figma** é uma ferramenta, dentre muitas outras existentes, para prototipagem de sites web. Com esta ferramenta, você pode: Modificar a estrutura do site, cores, tamanhos, imagens, textos etc.; Criar uma navegabilidade (navegação) entre as telas e simular.; Simular como o site vai se comportar em todos os tipo de telas, tais como computadores, tablets e celulares.; Trabalhar em conjunto com outras pessoas, simultaneamente, no mesmo projeto.

Ao final da prototipação do projeto, você pode exportar o site e terá já construída toda sua estrutura. Agora, com toda esta etapa de construção adiantada, você pode trabalhar apenas na inteligência e programação do site.

****Ionic:**