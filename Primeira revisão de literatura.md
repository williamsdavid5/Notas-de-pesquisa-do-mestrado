Vamos nos basear no [modelo](https://docs.google.com/document/d/1bY813sDopQMXs0lZf6XDTXxqafN_0ehB/edit?usp=sharing&ouid=100459640762631514330&rtpof=true&sd=true) fornecido na disciplina "Metodologia de Pesquisa 1", assim como o [modelo preenchido](https://drive.google.com/drive/folders/1I2Q4cehdME8fFrOy4knL7L2bvZBGekeW?usp=drive_link), e após isso, vamos escrever um artigo, conforme os [modelo](https://drive.google.com/drive/folders/1I2Q4cehdME8fFrOy4knL7L2bvZBGekeW?usp=drive_link) na pasta fornecida pela professora.

Com isso, seguem os metadados da pesquisa, pelo menos os que eu consegui desenvolver até esse ponto:

## Metadados de pesquisa
- Pesquisador: Williams David Estumano Duarte
- Tema: Revisão Sistemática da Literatura sobre Ambientes Experimentais para o Mundo do Wumpus: Uma Análise de Reutilização, Observabilidade e Portabilidade.
- Objetivos: Identificar trabalhos que implementam e testam agentes inteligentes no Mundo do Wumpus, avaliando o potencial de seus ambientes de simulação para servirem como plataformas reutilizáveis de teste por terceiros.

**Perguntas da revisão
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

## Artigos encontrados
De forma "bruta", os artigos que foram encontrados serão listados e comentados em [[Artigos Encontrados]].