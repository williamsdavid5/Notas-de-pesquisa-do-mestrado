
---
### TRABALHO 0
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
- Nível de detalhamento da arquitetura/metodologia do ambiente (0 a 2): 
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
- Nível de detalhamento da arquitetura/metodologia do ambiente (0 a 2): 1
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
- Nível de detalhamento da arquitetura/metodologia do ambiente (0 a 2): 1
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
- Nível de detalhamento da arquitetura/metodologia do ambiente (0 a 2): 1
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
- Nível de detalhamento da arquitetura/metodologia do ambiente (0 a 2): 
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