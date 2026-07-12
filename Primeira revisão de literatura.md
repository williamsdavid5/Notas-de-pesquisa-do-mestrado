Vamos nos basear no [modelo](https://docs.google.com/document/d/1bY813sDopQMXs0lZf6XDTXxqafN_0ehB/edit?usp=sharing&ouid=100459640762631514330&rtpof=true&sd=true) fornecido na disciplina "Metodologia de Pesquisa 1", assim como o [modelo preenchido](https://drive.google.com/drive/folders/1I2Q4cehdME8fFrOy4knL7L2bvZBGekeW?usp=drive_link), e após isso, vamos escrever um artigo, conforme os [modelo](https://drive.google.com/drive/folders/1I2Q4cehdME8fFrOy4knL7L2bvZBGekeW?usp=drive_link) na pasta fornecida pela professora.

O [meu protocolo de revisão](https://docs.google.com/document/d/1ISgyT3XCcX2fjKOeQf74d3CIGJOIJsJI/edit?usp=sharing&ouid=100459640762631514330&rtpof=true&sd=true) também foi criado para o compartilhamento em tempo real da pesquisa pelo meu orientador.

Com isso, seguem os metadados da pesquisa, pelo menos os que eu consegui desenvolver até esse ponto:

## Metadados de pesquisa
- Pesquisador: Williams David Estumano Duarte
- Tema: Revisão Sistemática da Literatura sobre Ambientes Experimentais para o Mundo do Wumpus: Uma Análise de Reutilização, Observabilidade e Portabilidade.
- Objetivos: Identificar trabalhos que implementam e testam agentes inteligentes no Mundo do Wumpus, avaliando o potencial de seus ambientes de simulação para servirem como plataformas reutilizáveis de teste por terceiros.

**Perguntas da revisão
- Qual é o propósito primário dos ambientes identificados na literatura: plataformas dedicadas ao teste por terceiros ou infraestruturas acessórias focadas na validação de agentes específicos?
- Como os ambientes descritos na literatura são parametrizados para a execução dos agentes?
- De que forma os resultados das simulações e o comportamento dos agentes são apresentados ao usuário?
- Com base nas arquiteturas e descrições fornecidas nos textos, como os trabalhos se classificam quanto ao potencial de reutilização e facilidade de adoção de seus ambientes por terceiros?

Fontes: IEEE Xplore, Google Scholar
Período de busca: 10/07/2026 - 
Intervalo de busca: 10 ou 15 anos

## As palavras chave

| Palavra-chave em Português | Sinônimos em Português                                                              | Palavra-chave em Inglês | Sinônimos em Inglês                                                                          |
| -------------------------- | ----------------------------------------------------------------------------------- | ----------------------- | -------------------------------------------------------------------------------------------- |
| Wumpus                     | Mundo de Wumpus, Mundo do Wumpus, Caverna do Wumpus                                 | Wumpus                  | Wumpus World, Wumpus-world, Wumpus cave                                                      |
| Agente Inteligente         | Agente de IA, Inteligência artificial, Sistema inteligente, Agente Autônomo, Agente | Intelligent Agent       | AI agent, Autonomous agent, Agent, Intelligent system, Agent                                 |
| Plataforma                 | Sistema, Protótipo, Ambiente, Simulador, Ferramenta, Arcabouço                      | Platform                | System, Prototype, Environment, Simulator, Tool, Framework                                   |
| Teste                      | Execução, Jogo, Partida, Avaliação, Validação, Experimento, Benchmark               | Test                    | Testing, Evaluation, Validation, Experiment, Execution, Run, Game, Match, Benchmark, Testbed |
## Strings de busca utilizadas
- "Wumpus": Utilizada no IEEE Xplore, pois notou-se uma baixíssima taxa de trabalhos publicados sobre esse tema. Com isso, optou-se por uma busca simplificada para analisar todos os trabalhos relacionados ao tema "Mundo de Wumpus".
- "Wumpus ("agent" OR "agente") ("platform" OR "environment" OR "simulator" OR "ambiente" OR "sistema") ("test" OR "evaluation" OR "experiment" OR "benchmark" OR "teste" OR "execução")": Utilizada no Google Scholar, considerando a sintaxe aceita e o seu limite de caracteres. Nesse caso, a palavra "Wumpus" já inclui todos os trabalhos relacionados ao tema, funcionando como o grande filtro dessa pesquisa.

## Critérios de inclusão e Exclusão

| Critérios                                                                                                                                                                                            | Tipo     |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| Estudos que abordem explicitamente o problema do Mundo do Wumpus como cenário ou estudo de caso principal                                                                                            | Inclusão |
| Estudos que descrevam o desenvolvimento, a implementação ou o teste de pelo menos um agente inteligente, de qualquer tipo, no ambiente do Mundo do Wumpus                                            | Inclusão |
| Estudos que forneçam descrições textuais, diagramas arquiteturais ou detalhes metodológicos sobre o ambiente computacional, simulador ou script utilizado para executar e coletar os dados do agente | Inclusão |
| Estudos cujo texto completo não esteja acessível para leitura.                                                                                                                                       | Exclusão |
| Estudos puramente teóricos ou matemáticos que mencionem o Mundo do Wumpus apenas como exemplo ilustrativo, sem implementar um agente ou descrever rodadas de execução/simulação                      | Exclusão |

**Justificativa:** Os três critérios de inclusão serão o filtro para a seleção de trabalhos que de fato desenvolvem e testam pelo menos um agente inteligente no mundo de wumpus e forneçam os detalhes disso, dessa forma, será possível extrair a informação de como esse teste e resultados são visualizados, e o quão fácil é o uso disso. Os dois critérios de exclusão servem como uma camada complementar para esse filtro, removendo da lista trabalhos que estão hospedados em sites pagos, e trabalhos que não desenvolvem esse sistema na prática.

## Critérios de qualidade
1. Transparência Arquitetural do Ambiente
	- 0: O autor apenas menciona que rodou o agente, sem dar nenhum detalhe do ambiente de execução.
	- 1: O autor descreve brevemente o ambiente em texto (ex: menciona a linguagem ou uma biblioteca), mas sem diagramas ou especificações profundas.
	- 2: Descrição detalhada, apresentando a lógica de funcionamento, requisitos do sistema, diagramas de blocos ou fluxo de execução.
2. Capacidade de Observabilidade e Visualização
	- 0: O sistema funciona como uma "caixa-preta" (apenas computa os dados e não mostra a execução).
	- 1: Visualização textual ou rudimentar (ex: logs brutos no terminal, _prints_ da matriz do grid via texto).
	- 2: Visualização gráfica, amigável e em tempo real do agente se movendo pelo Mundo do Wumpus.
3. Nível de interação e parametrização do usuário
	- 0: Mapa e parâmetros totalmente fixos no código.
	- 1: Permite customização parcial, mas exige modificar arquivos de configuração de texto (JSON, TXT, XML).
	- 2: Permite customização dinâmica e interativa (ex: alterar tamanho, probabilidade de poços ou posicionar elementos de forma amigável).
4. Prontidão para uso como Plataforma
	- 0: É apenas um script acessório acoplado ao agente do autor, incapaz de rodar outros algoritmos.
	- 1: O ambiente é isolado do agente, mas estruturado puramente como um pacote de código/API local para desenvolvedores.
	- 2: O sistema se apresenta ou tem potencial claro de uma ferramenta/plataforma pronta e acabada para uso por terceiros (independente de ser via desktop ou web).
5. Simplicidade de Replicação e Implantação
	- 0: Não há qualquer pista de como replicar; exige dependências obscuras ou ambiente altamente restrito; O trabalho apresenta apenas a descrição teórica, lógica ou conceitual do ambiente, sem fornecer o código-fonte ou o artefato executável; ou o repositório é inexistente, exigindo que terceiros programem o sistema do zero para replicá-lo.
	- 1: O código-fonte é fornecido, mas exige instalação local complexa, compilação manual, dependências obscuras, gerenciadores de pacotes específicos ou configuração manual de variáveis de ambiente.
	- 2: Implantação trivial, automatizada ou nula (ex: ambiente em container Docker pronto, ferramenta Web de acesso direto "zero instalação" ou executável de clique único).
## Artigos encontrados
De forma "bruta", os artigos que foram encontrados serão listados e comentados em [[Artigos Encontrados]].

Alguns artigos interessantes também foram encontrados no meio do caminho, que não se encaixavam no tema, mas que trazem boas ideias, então todos foram reunidos em [[Artigos interessantes]].