
---
### TRABALHO 1
1º) Metadados básicos
- Título: Non-Player Character Decision-Making With Prolog and Ontologies
- Ano: 2023
- Autores: Sylvain Lapeyrade; Christophe Rey
- Veículo: 2023 IEEE Conference on Games (CoG)
- Base: IEEE Xplore


2º) Contextualização do trabalho:
O artigo propõe uma abordagem para tomada de decisão para NPCs em jogos, utilizando uma abordagem declarativa Prolog e ontologias. Isso é testado em uma versão mais complexa do mundo de wumpus desenvolvida no Unity.

  
3º) Propósito primário do ambiente:
( x ) plataformas dedicadas ao teste por terceiros
(   ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Transparência Arquitetural do Ambiente (0 a 2): 2
	- Justificativa: Não é mencionado no texto do artigo, mas foi disponibilizado o link para um código de prova do ambiente Unity, assim como um vídeo de demonstração. Infelizmente o link não está mais acessível, mas o artigo ganha essa nota por disponibilizar.
- Capacidade de Observabilidade e Visualização (0 a 2): 2
	- Justificativa: Foi desenvolvida uma interface gráfica para a visualização da execução, com a perspectiva do agente e a visão geral do ambiente, uma visualização bem elaborada.
- Nível de interação e parametrização do usuário (0 a 2): 2
	- Justificativa: O usuário pode gerar um mundo aleatório se baseando em uma lógica de sementes, e escolher entre tipos de IA disponíveis no protótipo (IA baseada em lógica, baseada em instruções condicionais feitas à mão, máquinas de estados finitos e árvores de comportamento).
- Prontidão para uso como Plataforma (0 a 2): 2
	- Justificativa: O fato de apresentar os resultados em duas perspectivas, e a possibilidade de parametrização desse sistema pelo usuário, já caracteriza esse projeto como pronto ou parcialmente pronto para ser usado como uma plataforma de testes.
- Simplicidade de Replicação e Implantação (0 a 2): 2
	- Justificativa: Os autores fornecem o link para o código do ambiente de prova em Unity, por não estar mais acessível, não foi possível identificar o nível de facilidade de teste desse código, mas a nota é justificada pela própria possibilidade de acesso ao código fonte.

Nota recebida nessa avaliação: 10

---




---




---

### TRABALHO 0
1º) Metadados básicos
- Título: Interpreting Deep Q-Networks: A Rule-Based Comparison with First-Order Logic in Wumpus World
- Ano: 2024
- Autores: Filip Pawlicki, Kamil Dobies, Marcin Pucek, Karol Draszawka
- Veículo: TASK Quarterl, volume 8, number 4
- Base: Google Scholar / Bridge of Journals


2º) Contextualização do trabalho:
O objetivo central do artigo é enfrentar o desafio da interpretabilidade em modelos de aprendizado por reforço profundo, especificamente as redes Deep Q-Networks. O foco são aspectos da inteligência dos agentes, não a usabilidade da plataforma.
  
3º) Propósito primário do ambiente:
(   ) plataformas dedicadas ao teste por terceiros
( x ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Detalhamento do Ciclo de Execução e Operação (0 a 2): 2
	- Justificativa: Os autores não detalham o processo de execução e apresentação do resultado das execução, não é descrito um passo a passo mínimo de como executar o código, mas a nota se justifica pela própria disponibilização de todos os arquivos de código, o que dá a possibilidade de saber como o processo de execução é feito.
- Capacidade de Observabilidade e Visualização (0 a 2): 2
	- Justificativa: Não são dados detalhes no artigo, mas ao que se pode notar no código, é feita a visualização da execução do agente, mesmo que de forma mais simplificada. Os resultados gerais também são apresentados com uma certa variação de opções, como uma tabela de resultados, apresentada no artigo.
- Nível de interação e parametrização do usuário (0 a 2): 0
	- Justificativa: A parametrização é totalmente via código.
- Prontidão para uso como Plataforma (0 a 2): 0
	- Justificativa: Apesar de exibir a execução em uma interface gráfica, esse é o único aspecto que é exibido, o restante é tudo definido via código, tornando um sistema muito longe de ser uma plataforma de testes.
- Simplicidade de Replicação e Implantação (0 a 2): 1
	- Justificativa: Todos os códigos são disponibilizados pelos autores no github, permitindo a fácil replicação da ferramenta.

Nota recebida nessa avaliação: 5

---
### TRABALHO 0
1º) Metadados básicos
- Título: Intention Reconsideration in Wumpus World And Intentional Inference in Adolescents
- Ano: 2018
- Autores: Carlos Pelta
- Veículo: BRAIN. Broad Research In Artificial Intelligence And Neuroscience
- Base: Google Scholar / brain.edusoft.ro


2º) Contextualização do trabalho:
O mundo de wumpus foi um cenário de teste psicológico em adolescentes, que buscava entender como a adolescência afeta a inferência intencional e a reconsideração de intenções. a versão clássica e uma versão levemente modificada do mundo de wumpus foram desenvolvidas, e os adolescentes acompanhavam execuções e tentavam prever o comportamento do agente, que foi desenvolvido para ter um comportamento mais cauteloso.
  
3º) Propósito primário do ambiente:
( x ) plataformas dedicadas ao teste por terceiros
(   ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Detalhamento do Ciclo de Execução e Operação (0 a 2): 2
	- Justificativa: O foco do artigo não é programação ou inteligência artificial, mas analisar as tomadas de decisão dos participantes, porém é descrito como a visualização é feita e algumas capturas de tela são apresentadas, mostrando que os resultados são exibidos graficamente. O texto também menciona que os participantes foram distribuídos em computadores, instruções foram passadas e um manual foi disponibilizado, indicando que foi desenvolvido um software com um certo nível de simplicidade.
- Capacidade de Observabilidade e Visualização (0 a 2): 2
	- Justificativa: O fato de apresentar a execução graficamente já justifica a nota.
- Nível de interação e parametrização do usuário (0 a 2): 0
	- Justificativa: Muitos parâmetros são fixos no código, como a dimensão do tabuleiro, tempo de espera entre os passos, número de passos até o wumpus despertar e até o tamanho da janela apresentada. O usuário só consegue reiniciar a execução e escolher entre os modos de passo automático ou manual. A geração do mundo é aleatória e automática a cada execução, ou seja, o jogo sempre começa com um mundo diferente.
- Prontidão para uso como Plataforma (0 a 2): 1
	- Justificativa: A apresentação visual da execução já é um grande passo para o uso desse sistema por terceiros, mas por ainda ser um software fechado, com nível de parametrização baixo ou nulo, podemos concluir que esse sistema ainda não está pronto para o uso como plataforma.
- Simplicidade de Replicação e Implantação (0 a 2): 0
	- Justificativa: Um código é anexado ao artigo, mas partes cruciais estão faltando, sendo necessária a replicação da programação para que o sistema funcione.

Nota recebida nessa avaliação: 5

---

### TRABALHO 0
1º) Metadados básicos
- Título: LLM-Cave: A benchmark and light environment for large language models reasoning and decision-making system
- Ano: 2025
- Autores: Huanyu Li, Zongyuan Li, Wei Huang, Xian Guo
- Veículo: arXiv
- Base: Google Scholar / arXiv


2º) Contextualização do trabalho:
Os autores propõem uma estrutura de benchmark leve projetado para avaliar e aprimorar as capacidades de raciocínio de modelos de linguagem LLM. O LLM-Cave utiliza a lógica do mundo de wumpus como ambiente de teste. Vale ressaltar que o "agente" aqui seria o LLM que iria testar a plataforma.
  
3º) Propósito primário do ambiente:
(   ) plataformas dedicadas ao teste por terceiros
( x ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Detalhamento do Ciclo de Execução e Operação (0 a 2): 2
	- Justificativa: Os autores detalham tanto quanto é possível o processo de execução, sendo via linhas, que retornam detalhes das execuções a cada passo, como as percepções. Um exemplo dessa estrutura é disponibilizado no artigo, e uma captura da janela de apresentação dessa informação, é exibida.
- Capacidade de Observabilidade e Visualização (0 a 2): 1
	- Justificativa: Não foi desenvolvida uma interface gráfica para a visualização da execução, mas é possível ver os resultados de cada passo com um log personalizado, contendo informações completas sobre o estado do agente a cada passo.
- Nível de interação e parametrização do usuário (0 a 2): 0
	- Justificativa: Os autores mencionam parâmetros que foram usados nos testes, mas não mencionam como eles podem ser definidos na execução, deixando aberta a possibilidade de ser via código.
- Prontidão para uso como Plataforma (0 a 2): 0
	- Justificativa: O sistema não desenvolve visualização gráfica, o artigo não cita em nenhum momento a possibilidade configuração da execução por parte do usuário. 
- Simplicidade de Replicação e Implantação (0 a 2): 1
	- Justificativa: Os autores disponibilizam o link direto ao repositório dos códigos, mas infelizmente não está mais acessível.

Nota recebida nessa avaliação: 4


### TRABALHO 0
1º) Metadados básicos
- Título: Algoritmo Genético como Mecanismo de Aprendizagem do Agente na Resolução do Mundo de Wumpus
- Ano: 2019
- Autores Natália Freitas Araújo, Adriano A. Addario dos Santos, Otávio Noura Teixeira
- Veículo: Trabalho de Curso – Faculdade de Engenharia da Computação, Universidade Federal do Pará
- Base: Biblioteca Digital de Monografias - UFPA


2º) Contextualização do trabalho:
Utilizando a técnica do algoritmo genético para o desenvolvimento de um agente baseado em aprendizagem, esse agente foi testado no cenário do mundo de wumpus. O foco do trabalho é a investigação da eficácia de um algoritmo genético para a resolução do problema do mundo de wumpus. 4.200 execuções foram feitas e os resultados foram mistos, pois a técnica aplicada pelo autor se mostrou muito eficiente em ambientes menores, mas com um mal desempenho em ambientes mais desafiadores.
  
3º) Propósito primário do ambiente:
(   ) plataformas dedicadas ao teste por terceiros
( x ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Detalhamento do Ciclo de Execução e Operação (0 a 2): 2
	- Justificativa: A descrição da operação foi altamente detalhada, com toda a parametrização utilizada pelos autores e a forma como os resultados são apresentados, não foi citado explicitamente se a execução é apresentada em tempo real para o usuário, mas isso já era esperado baseado na proposta do artigo. Com a informação dessa grande quantidade de execuções realizadas, podemos concluir que as execuções são feitas em segundo plano, e os resultados são salvos automaticamente em alguns formatos úteis.
- Capacidade de Observabilidade e Visualização (0 a 2): 1
	- Justificativa: Os autores não chegam a desenvolver uma interface gráfica amigável para a visualização da execução, pois a proposta do trabalho é o teste dos agentes, não a usabilidade. No entanto, a geração e apresentação dos ambientes em forma de gráficos, e a geração automática de gráficos dos resultados das execuções, justificam a nota.
- Nível de interação e parametrização do usuário (0 a 2): 1
	- Justificativa: O artigo não propõe uma plataforma de testes por terceiros, mas ainda há um nível baixo de parametrização, ainda que manual.  A nota se justifica pelo gerador aleatório de mundos, que permite com que o usuário "escolha" um ambiente de testes, o gerador salva o mundo em formato de imagem e .csv, permitindo que o usuário visualize e use aquele mapa na execução.
- Prontidão para uso como Plataforma (0 a 2): 0
	- Justificativa: O artigo não propõe o uso de uma plataforma por terceiros, apenas testa os agentes.
- Simplicidade de Replicação e Implantação (0 a 2): 0
	- Justificativa: A proposta do artigo é o desenvolvimento e geração em massa de dados de teste, então não é apresentado nenhum código, seja lógico ou em linguagem de programação, nenhum link de repositório ou até mesmo um diagrama estrutural do ambiente de testes.

Nota recebida nessa avaliação: 4


---
### TRABALHO 0
1º) Metadados básicos
- Título: A multi context dynamic test bed for simulating real world constraints in agents' teamwork
- Ano: 2012
- Autores: Sajjad Salehi; Mohammad Taghi Saffar; Fattaneh Taghiyareh; Kambiz Badie
- Veículo: 6th International Symposium on Telecommunications (IST)
- Base: IEEE Xplore


2º) Contextualização do trabalho:
Os autores testam múltiplos agentes atuando ao mesmo tempo no mundo de wumpus, simulando restrições e apresentando os resultados do trabalho em equipe. Esse projeto tem a proposta de ser fácil de usar e tem o objetivo de ser um ambiente de testes de quaisquer assuntos relacionados à ação conjunta de múltiplos agentes. 

  
3º) Propósito primário do ambiente:
( x ) plataformas dedicadas ao teste por terceiros
(   ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Detalhamento do Ciclo de Execução e Operação (0 a 2): 1
	- Justificativa: Os autores não apresentam passos lógicos ou diagramas sobre como a execução é feita e exibida, mas demonstram a configuração inicial da execução, mostrando capturas de tela da interface gráfica de configuração dos testes, porém para por aí, não dão nenhum detalhe sobre a exibição dos resultados.
- Capacidade de Observabilidade e Visualização (0 a 2): 0
	- Justificativa: Os autores não mencionam se a execução é exibida ao usuário ou como os testes são apresentados.
- Nível de interação e parametrização do usuário (0 a 2): 2
	- Justificativa: Alto nível de parametrização, tanto via interface gráfica, quanto via código, pois o sistema fornece classes para o desenvolvimento relativamente fácil dos agentes pelo próprio usuário.
- Prontidão para uso como Plataforma (0 a 2): 1
	- Justificativa: Apesar de ter um alto nível de parametrização, ainda seria necessário desenvolver agentes para realizar os testes, isso indica que o sistema não foi feito para ser usado por usuários comuns. Sobre a visualização da execução e resultados, como mencionado, os autores não detalham.
- Simplicidade de Replicação e Implantação (0 a 2): 0
	- Justificativa: Apenas pistas são dadas sobre como replicar os testes, o detalhamento é até relativamente alto, fornecendo em alguns momentos os nomes de classes e uma estrutura lógica do padrão de projeto, mas não fornece nenhum código fonte, mesmo de forma parcial, ou diagrama lógico para o funcionamento do sistema.

Nota recebida nessa avaliação: 4

---
### TRABALHO 0
1º) Metadados básicos
- Título: A Simple Integration of Epistemic Logic and Reinforcement Learning
- Ano: 2025
- Autores: Thorsten Engesser , Thibaut Le Marre, Emiliano Lorini, François Schwarzentruber, Bruno Zanuttini
- Veículo: Proc. of the 24th International Conference on Autonomous Agents and Multiagent Systems (AAMAS 2025) (pp. 686-694).
- Base: Google Scholar


2º) Contextualização do trabalho:
Os autores abordam o desafio de integrar o aprendizado de máquina com a representação do conhecimento. Eles introduzem um framework que utiliza bases de crenças para representar o estado subjetivos de um agente. Essa estrutura é formalizada em um modelo chamado BB-POMDP (Belief Base POMDP), onde os estados e observações são definidos por fórmulas lógicas. O mundo de Wumpus é o ambiente de teste.
  
3º) Propósito primário do ambiente:
(   ) plataformas dedicadas ao teste por terceiros
( x ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Detalhamento do Ciclo de Execução e Operação (0 a 2): 2
	- Justificativa: Além do alto nível de detalhes sobre o processo, os autores disponibilizaram um acesso direto ao código.
- Capacidade de Observabilidade e Visualização (0 a 2): 0
	- Justificativa: Nada indica que o sistema exiba a execução do agente no jogo, nem mesmo via texto.
- Nível de interação e parametrização do usuário (0 a 2): 0
	- Justificativa: Toda a parametrização é definida pela lógica BB-POMDP, isso é muito longe do ideal para um usuário comum.
- Prontidão para uso como Plataforma (0 a 2): 0
	- Justificativa: O sistema é totalmente lógico, o que o deixa muito longe de ser usado como uma plataforma de testes.
- Simplicidade de Replicação e Implantação (0 a 2): 1
	- Justificativa: Os autores disponibilizam um link direto ao código fonte do sistema.

Nota recebida nessa avaliação: 3

---
### TRABALHO 0
1º) Metadados básicos
- Título: Modeling of the Wumpus World to Evaluate the Difficulty Level of the Game using Coloured Petri Net
- Ano:  2025
- Autores: Ali Naghash Asadi; Mahrou Pourjani; Ali Mirsaeed Ghazi
- Veículo: Journal of Algorithms and Computation
- Base: Google Scholar / jac.ut.ac.ir


2º) Contextualização do trabalho:
Os autores propõem um modelo de agente aplicado ao mundo de wumpus que utiliza redes Petri Coloridas. O modelo permite que desenvolvedores de games simulem vários cenários de jogos utilizando esse algoritmo.
  
3º) Propósito primário do ambiente:
(   ) plataformas dedicadas ao teste por terceiros
( x ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Detalhamento do Ciclo de Execução e Operação (0 a 2): 2
	- Justificativa: A execução é feita na ferramenta "CPN Tools", e as redes Petri são disponibilizadas no artigo, assim como outros códigos e diagramas.
- Capacidade de Observabilidade e Visualização (0 a 2): 0
	- Justificativa: A visualização é feita através da lógica de redes Petri, a justificativa para a nota se dá pela necessidade de adquirir o conhecimento prévio sobre redes Petri antes executar.
- Nível de interação e parametrização do usuário (0 a 2): 0
	- Justificativa: Toda a interação é feita através da ferramenta CPN Tools, para que isso seja feito, necessita-se de conhecimento prévio sobre redes Petri.
- Prontidão para uso como Plataforma (0 a 2): 0
	- Justificativa: O trabalho não propõe uma ferramenta, utilizando uma ferramenta de terceiros.
- Simplicidade de Replicação e Implantação (0 a 2): 0
	- Justificativa: Os autores disponibilizam detalhes sobre o desenvolvimento do projeto, porém a necessidade do conhecimento prévio sobre redes Petri comprometem a replicação.

Nota recebida nessa avaliação: 2

---
### TRABALHO 0
1º) Metadados básicos
- Título: A Logical Agent Approach to Solving the Wumpus World Problem: An Analysis of Game Trees
- Ano: 2023
- Autores: Mrudgandh Kumbhar; Vinay Vishwakarma; Reetu Jain;
- Veículo: 2023 9th International Conference on Advanced Computing and Communication Systems (ICACCS)
- Base: IEEE Xplore

2º) Contextualização do trabalho:
De forma simplificada, o trabalho busca resolver o problema do mundo de wumpus utilizando o algoritmo Minimax para gerar árvores de jogo e para encontrar a melhor estratégia de ação. O objetivos dos autores é demonstrar que a solução proposta é uma estratégia possível para o desenvolvimento de agentes inteligentes, melhorando o seu raciocínio sobre o ambiente com lógica de primeira ordem.

3º) Propósito primário do ambiente:
(   ) plataformas dedicadas ao teste por terceiros
( x ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Detalhamento do Ciclo de Execução e Operação (0 a 2): 1
	- Justificativa: O detalhamento não é nulo, mas incompleto, os autores descrevem um código lógico sobre como o agente toma as decisões, mas não dão detalhes sobre a execução e visualização dos resultados, não apresentam códigos nem diagramas sobre a arquitetura do ambiente, nem cita de forma aprofundada as bibliotecas.
- Capacidade de Observabilidade e Visualização (0 a 2): 0
	- Justificativa: Apenas faz o processamento mas não mostra de forma visual o agente tomando as decisões pelo mundo, mesmo pelo terminal. Na verdade os autores nem mesmo dão detalhes sobre como isso é visualizado, mas pelas suas descrições, notamos que esse sistema é 100% código.
- Nível de interação e parametrização do usuário (0 a 2): 0
	- Justificativa: o foco do trabalho é totalmente a resolução do problema utilizando algoritmo, então os autores não desenvolveram uma entrada de dados amigável, nem mesmo via terminal ou arquivo de texto.
- Prontidão para uso como Plataforma (0 a 2): 0
	- Justificativa: Projeto puramente lógico, muito longe de qualquer tipo de uso como plataforma de testes.
- Simplicidade de Replicação e Implantação (0 a 2): 0
	- Justificativa: O máximo de descrição que os autores fornecem sobre o código é a sua lógica de tomada de decisão, mas não fornecem nenhum link de repositório, nem mesmo algum trecho incompleto do código no artigo ou apêndice, sendo necessária a escrita do zero.

Nota recebida nessa avaliação: 1


---
### TRABALHO 0
1º) Metadados básicos
- Título: Colored Knowledge Petri Nets and Logical Inference
- Ano: 2021
- Autores: Kaicheng Tan; Jiliang Luo; Hongbin Zhang; Xinjie Lin; Enhui Zheng
- Veículo: 2021 IEEE International Conference on Networking, Sensing and Control (ICNSC)
- Base: IEEE Xplore

2º) Contextualização do trabalho:
Os autores desenvolvem um agente que tomas as decisões utilizando uma lógica com redes Petri e conhecimento colorido visando apresentar um modelo menor e concreto em comparação com uma rede Petri de conhecimento. Baseado nisso, o motor de inferência de um agente inteligente é proposto utilizando essa lógica, demonstrando a sua eficácia no mundo de wumpus. 
  
3º) Propósito primário do ambiente:
(   ) plataformas dedicadas ao teste por terceiros
( x ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Detalhamento do Ciclo de Execução e Operação (0 a 2): 1
	- Justificativa: Os autores descrevem a forma que o mundo de wumpus e inteligência do agente são interpretados como redes petri, mas não detalha de maneira técnica como foi realizada a execução.
- Capacidade de Observabilidade e Visualização (0 a 2): 0
	- Justificativa: Os resultados são apresentados e ilustrados pelos próprios autores, mas não é citado no texto como isso é apresentado pelo código.
- Nível de interação e parametrização do usuário (0 a 2): 0
	- Justificativa: Nenhum nível de interação é inserido nesse sistema.
- Prontidão para uso como Plataforma (0 a 2): 0
	- Justificativa: O trabalho não se propõe a desenvolver uma plataforma, nem mesmo um código, o seu foco central é puramente lógica.
- Simplicidade de Replicação e Implantação (0 a 2): 0
	- Justificativa: Requer um nível de conhecimento mais avançado sobre o assunto para a replicação, o autor não disponibiliza nenhum código via repositório ou anexo.

Nota recebida nessa avaliação: 1

---
### TRABALHO 0
1º) Metadados básicos
- Título: Neural network agents trained by declarative programming tutors
- Ano: 2024
- Autores: Julian Szymanski; Jan Dobrosolski; Higinio Mora; Karol Draszawka
- Veículo: 2024 IEEE Congress on Evolutionary Computation (CEC)
- Base: IEEE Xplore

2º) Contextualização do trabalho:
O artigo é um estudo experimental sobre o desenvolvimento de um agente baseado em redes neurais, o mundo de wumpus é usado para testar a eficácia desses agentes. O foco desse trabalho é o desenvolvimento e teste de agentes, apresentando um solução para um problema complexo com o uso otimizado de memória.
  
3º) Propósito primário do ambiente:
(   ) plataformas dedicadas ao teste por terceiros
( x ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Detalhamento do Ciclo de Execução e Operação (0 a 2): 1
	- Justificativa: O trabalho detalha bem sobre como o agente é construído, apresentando as ferramentas que foram utilizadas, como o Python e Prolog, e a biblioteca pySwip, apesar de não ser tão específico sobre esse processo, porém não apresenta muitos detalhes sobre a execução do agente no ambiente. Temos um exemplo de uma saída da execução, em um terminal ou arquivo de texto, dando a entender que a execução é feita via terminal ou diretamente por código, mas isso não é citado diretamente pelos autores.
- Capacidade de Observabilidade e Visualização (0 a 2): 0
	- Justificativa: O foco do autor é a coleta de dados, então a execução do agente é realizada rapidamente sem a possibilidade de visualização em tempo real. É mencionada a coleta de dados gerados das execuções, e até demonstrado um exemplo de saída desses dados, mas em nenhum lugar é mencionado sobre como os dados são apresentados ao usuário.
- Nível de interação e parametrização do usuário (0 a 2): 0
	- Justificativa: O autor não descreve nenhuma forma de parametrização de um possível usuário para a execução, nem nenhum nível de interação sobre o sistema.
- Prontidão para uso como Plataforma (0 a 2): 0
	- Justificativa: O trabalho foca totalmente na lógica do agente, então o projeto proposto não chega perto de uma plataforma de testes, mesmo minimamente pronta para uso.
- Simplicidade de Replicação e Implantação (0 a 2): 0
	- Justificativa: O autor menciona as tecnologias e a lógica do código, mas não apresenta linhas de código ou link do que foi desenvolvido, apesar de referenciar o repositório de um simulador Prolog do mundo de wumpus.

Nota recebida nessa avaliação: 1

---

### TRABALHO 0
1º) Metadados básicos
- Título: Algoritmos Genéticos aplicado ao mundo de Wumpus: uma comparação entre agentes baseados em regras e agentes inteligentes
- Ano: 2021
- Autores: Victor S. Martins, Julio Cezar Gonçalves de Freitas, Ingrid Nery Mendes, Otávio Noura Teixeira
- Veículo: Anais da I Escola Regional de Alto Desempenho Norte 2 (ERAD-NO2) e I Escola Regional de Aprendizado de Máquina e Inteligência Artificial Norte 2 (ERAMIA-NO2) — publicado pela SBC (Sociedade Brasileira de Computação)
- Base: Google Scholar, SOL / SBC OpenLib (Biblioteca Digital da SBC)


2º) Contextualização do trabalho:
Esse trabalho testa algumas variações de algoritmos genéticos no mundo de wumpus, apresentando os resultados e buscando identificar a melhor solução entre as soluções propostas.

  
3º) Propósito primário do ambiente:
(   ) plataformas dedicadas ao teste por terceiros
( x ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Detalhamento do Ciclo de Execução e Operação (0 a 2): 1
	- Justificativa: Os autores descrevem o planejamento dos testes e parâmetros de execução, mas não detalham como os resultados são exibidos ao usuário, isso é esperado de um artigo que foca no desempenho do agente em vez do ambiente de teste.
- Capacidade de Observabilidade e Visualização (0 a 2): 0
	- Justificativa: Não foi descrita de nenhuma forma a Observabilidade das execuções e dos resultados, dando a entender que as execuções foram feitas em segundo plano.
- Nível de interação e parametrização do usuário (0 a 2): 0
	- Justificativa: Os autores deixam claro que os parâmetros são rigorosamente estáticos.
- Prontidão para uso como Plataforma (0 a 2): 0
	- Justificativa: O ambiente de testes não foi descrito, o que é um forte indício de que esse ambiente é puramente código.
- Simplicidade de Replicação e Implantação (0 a 2): 0
	- Justificativa: Nenhum código é fornecido, nem uma estrutura lógica alguma pista de como replicar o ambiente de testes em termos de programação.

Nota recebida nessa avaliação: 1

---

### TRABALHO 0
1º) Metadados básicos
- Título: Better Apprenticeship Learning with LLM Explanations
- Ano: 2024
- Autores: Rynaa Grover, Aryan Vats, Nina Moorman, Aviral Agrawal, Matthew Gombolay
- Veículo: Proceedings of the AAAI Symposium Series
- Base: Google Scholar / ojs.aaai.org


2º) Contextualização do trabalho:
O objetivo central do trabalho é encontrar uma solução para a forma como usuários leigos ensinam robôs, especialmente robôs de assistência para idosos. Isso seria feito mediante uma LLM, que iria receber as demonstrações por parte dos usuários e se comunicar com eles para corrigir as instruções e garantir que os robôs recebam os comandos da forma mais precisa quanto for possível. O mundo de wumpus é utilizado para testar a solução proposta, em que os usuários iriam orientar os agentes para que aprendam a corrigir a execução.
  
3º) Propósito primário do ambiente:
(   ) plataformas dedicadas ao teste por terceiros
( x ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Detalhamento do Ciclo de Execução e Operação (0 a 2): 0
	- Justificativa: é mencionado que parte do procedimento consiste em coletar dados de jogo do próprio usuário para alimentar inicialmente o agente, mas não é detalhado como isso foi feito.
- Capacidade de Observabilidade e Visualização (0 a 2): 1
	- Justificativa: O artigo simplesmente menciona que os participantes podem escolher assistir o agente jogando, mas não dá nenhum detalhe adicional nem apresenta capturas de tela. Porém o fato dos autores mencionarem isso, justifica a nota.
- Nível de interação e parametrização do usuário (0 a 2): 1
	- Justificativa: É um caso diferente, como o jogo está sendo testado focando nas instruções, as próprias instruções dos participantes podem ser consideradas como uma interação, o que é bem diferente do usual. Tirando isso, os outros parâmetros são fixos no código.
- Prontidão para uso como Plataforma (0 a 2): 0
	- Justificativa: Ainda está muito distante de ser usado como uma plataforma de testes de agentes no mundo de wumpus, visto que sua proposta central é as instruções dos agentes.
- Simplicidade de Replicação e Implantação (0 a 2): 0
	- Justificativa: As descrições são totalmente teóricas e algorítmicas .

Nota recebida nessa avaliação: 2

---
### TRABALHO 0
1º) Metadados básicos
- Título: Intelligent agents capable of developing memory of their environment
- Ano: 
- Autores: Gul Muhammad Khan, Julian F. Miller, and David M. Halliday
- Veículo: 
- Base: Google Scholar / Research Gate


2º) Contextualização do trabalho:
Os autores desenvolveram um modelo computacional do cérebro inspirado na neurociência, o agente se desenvolve durante a interação com o mundo de wumpus, esse desenvolvimento possui um certo nível de semelhança com o desenvolvimento real no cérebro, em que neurônios nascem e morrem conforme aprendemos.
  
3º) Propósito primário do ambiente:
(   ) plataformas dedicadas ao teste por terceiros
( x ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Detalhamento do Ciclo de Execução e Operação (0 a 2): 0
	- Justificativa: Os parâmetros do experimento são muito bem detalhados, mas a operação do código do jogo não é mencionada em nenhum momento.
- Capacidade de Observabilidade e Visualização (0 a 2): 0
	- Justificativa: Os autores não deixam claro se a execução é exibida, o que nós vemos são capturas de tela da evolução do cérebro do agente, isso é muito interessante e é o foco do trabalho, mas o nosso foco é a visualização da execução, e não vemos isso descrito de forma clara no artigo.
- Nível de interação e parametrização do usuário (0 a 2): 0
	- Justificativa: Como não foi detalhado o ciclo de operação, não temos informações sobre a parametrização, de acordo com as descrições, podemos concluir que o sistema é totalmente voltado ao teste do agente.
- Prontidão para uso como Plataforma (0 a 2): 0
	- Justificativa: O sistema é totalmente voltado ao experimento, não temos informações sobre o ciclo de operação do código nem visualização, então podemos concluir que o sistema é completamente linhas de código.
- Simplicidade de Replicação e Implantação (0 a 2): 0
	- Justificativa: Apesar de descrever o experimento, não temos descrições técnicas que permitam uma replicação ou uso desse sistema por terceiros.

Nota recebida nessa avaliação: 0

---
### TRABALHO 0
1º) Metadados básicos
- Título: Individual vs. Joint Perception: a Pragmatic Model of Pointing as Communicative Smithian Helping
- Ano: 2021
- Autores: Kaiwen Jiang and Stephanie Stacy and Chuyu Wei and Adelpha Chan and Federico Rossano and Yixin Zhu and Tao Gao
- Veículo: arxiv
- Base: Google Scholar / arxiv


2º) Contextualização do trabalho:
O trabalho modela um agente em que, sua crença sobre o ambiente é atualizada por observações, e desenvolve um sistema de apontar para a comunicação multiagente.
  
3º) Propósito primário do ambiente:
(   ) plataformas dedicadas ao teste por terceiros
( x ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Detalhamento do Ciclo de Execução e Operação (0 a 2): 0
	- Justificativa: Não são dados detalhes sobre a usabilidade do ambiente de testes, já que o trabalho foca na lógica dos agentes.
- Capacidade de Observabilidade e Visualização (0 a 2): 0
	- Justificativa: O foco do trabalho é a inteligência dos agentes, então não foi desenvolvida nenhuma forma de visualização. Os autores mencionam métrica e apresentam gráficos, mas em nenhum momento isso é descrito como uma saída gerada automaticamente pela ferramenta.
- Nível de interação e parametrização do usuário (0 a 2): 0
	- Justificativa: Por ser completamente código, não há nenhum nível de interação de um possível usuário com a plataforma de testes.
- Prontidão para uso como Plataforma (0 a 2): 0
	- Justificativa: Por ser totalmente código, ainda está muito distante de ser uma plataforma.
- Simplicidade de Replicação e Implantação (0 a 2): 0
	- Justificativa: Nenhum código fonte é apresentado em anexo, ou mencionado no texto, nenhuma estrutura lógica do sistema foi apresentada no artigo, as descrições são puramente lógicas.

Nota recebida nessa avaliação: 0


Base para preenchimento
### TRABALHO 00
1º) Metadados básicos
- Título:
- Ano:
- Autores:
- Veículo:
- Base:


2º) Contextualização do trabalho:

  
3º) Propósito primário do ambiente:
(   ) plataformas dedicadas ao teste por terceiros
(   ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Detalhamento do Ciclo de Execução e Operação (0 a 2): 
	- Justificativa: 
- Capacidade de Observabilidade e Visualização (0 a 2): 
	- Justificativa: 
- Nível de interação e parametrização do usuário (0 a 2): 
	- Justificativa:
- Prontidão para uso como Plataforma (0 a 2): 
	- Justificativa:
- Simplicidade de Replicação e Implantação (0 a 2): 
	- Justificativa: 

Nota recebida nessa avaliação: 






Esse foi removido depois:
### TRABALHO 0
1º) Metadados básicos
- Título: AFLUX Agent for the Wumpus World
- Ano: 
- Autores: Michael Thielscher
- Veículo:
- Base: Google Scholar


2º) Contextualização do trabalho:
O artigo descreve o desenvolvimento de um agente inteligente para o clássico ambiente do Mundo de Wumpus utilizando o FLUX, um método de programação de alto nível voltado para o design de agentes que raciocinam logicamente sob condições de conhecimento incompleto
  
3º) Propósito primário do ambiente:
(   ) plataformas dedicadas ao teste por terceiros
( x ) infraestruturas acessórias focadas na validação de agentes específicos

4º) Critérios de qualidade:
- Detalhamento do Ciclo de Execução e Operação (0 a 2): 2
	- Justificativa: Todo o ciclo de execução é definido pela linguagem lógica apresentada no trabalho, e como o foco do artigo é justamente o uso dessa linguagem, temos um nível alto de detalhamento quanto à execução do agente no mundo, mesmo que não haja detalhes técnicos, como o início da execução do próprio código.
- Capacidade de Observabilidade e Visualização (0 a 2): 0
	- Justificativa: Temos representações do ambiente e tabelas no artigo, mas em nenhum momento é mencionado que são representações geradas pelo próprio ambiente de testes.
- Nível de interação e parametrização do usuário (0 a 2): 0
	- Justificativa: O nível de parametrização é relativamente alto, mas isso é feito através da linguagem mostrada no artigo.
- Prontidão para uso como Plataforma (0 a 2): 0
	- Justificativa: O sistema não se propõe a ser uma plataforma de testes, toda a parametrização é definida via código, e não há descrições indicando que os resultados saiam de forma amigável para um possível usuário.
- Simplicidade de Replicação e Implantação (0 a 2): 2
	- Justificativa: Além de detalhar a programação lógica do agente e da execução no próprio artigo, é disponibilizado um link para os arquivos de código. Infelizmente está inacessível, mas essa disponibilização justifica a nota.

Nota recebida nessa avaliação: 4
