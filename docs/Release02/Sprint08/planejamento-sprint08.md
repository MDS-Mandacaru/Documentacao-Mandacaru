# Planejamento

|Número da sprint 	| 08|
|---------|-|
|Data de início 	| 11/06/2018|
|Data de término 	| 25/06/2018|

### Reunião
**Data:** 11/06

**Horário:** 10:00 às 11:30

**Local:** Via *hangouts* (vídeo chamada do Google)

### Dados da Sprint
* Horário daily meeting: 20h:00

### Papéis
* Scrum Master: Luís Claudio T. Lima

* Development time: Aline Laureano, William Elias, Felipe Agustini e Marcelo Magalhães

## Backlog da Sprint
Sprint dedicada as dividas técnicas da RELEASE 1 e a estudo para criar a funcionalidade de raspadinha na avaliação gRAT.
<br/>
***  
 **Issue #37** [US06] - Eu como professor ou aluno, caso haja empate de nota entre grupos de uma disciplina, desejo visualizar esses grupos pertencendo a mesma colocação.<br/>

    Critérios de aceitação:
    
    - O software consegue verificar se há empate de dois ou mais grupos na 1ª colocação do Ranking.
    
    - O software consegue verificar se há empate de dois ou mais grupos na 2ª colocação do Ranking.
    
    - O software consegue verificar se há empate de dois ou mais grupos na 3ª colocação do Ranking.
    
    - Caso haja empate na 1ª posição, todos os grupos desse empate aparecem com o troféu de primeiro lugar.
    
    - Caso haja empate na 2ª posição, todos os grupos desse empate aparecem com o troféu de segundo lugar.
    
    - Caso haja empate na 3ª posição, todos os grupos desse empate aparecem com o troféu de terceiro lugar.
***
 **Issue #38** [US07] - Eu, como professor, só consigo fechar uma disciplina caso todas as sessões relacionadas a ela estejam fechadas.<br/>

    Critérios de aceitação:
    
    - O software verifica se ha sessões abertas no momento em que uma disciplina e fechada.

    - Não deve ser permitido que uma disciplina seja fechada caso existam sessões abertas.

    - O software apresenta uma mensagem solicitando ao professor que feche as sessões abertas antes de finalizar a disciplina.
***
 **Issue #39** [EN01] - O software deve apresentar uma cobertura de testes unitários. <br/>
    
    Critérios de aceitação:

    - Feitos os testes unitários da aplicação hall of fame.

    - Feitos os testes unitários da aplicação ranking.

    - Feitos os testes unitários da funcionalidade de raspadinha da avaliação gRAT.
***
 **Issue #40** [US08] - Eu como usuário desejo ter acesso ao hall da fama de qualquer disciplina. <br/>
   
    Critérios de aceitação:
 
    - Qualquer usuário deve conseguir visualizar o hall da fama de todas as disciplinas cadastradas a qualquer momento.

***
 **Issue #41** [EN02] - O software deve cadastrar na model HallOfFame a lista de alunos pertencente a sua disciplina para fins de log. <br/>
   
    Critérios de aceitação:
 
    - Criado o atributo que armazena a lista de alunos.

    - O software armazena a lista de alunos na model HallOfFame assim que a disciplina e fechada.
 
***
 **Issue #45** [US09] - Eu, como estudante, desejo ter o feedback de uma pergunta respondida durante uma avaliação gRAT por meio de uma raspadinha. <br/>
   
    Critérios de aceitação:
 
    - Após cada submissão de uma resposta durante uma avaliação gRAT, o estudante tem acesso a uma raspadinha - uma imagem que pode ser "raspada" para que se visualize o que ela esconde.

    - Depois de raspar a raspadinha é apresentado um feedback de desempenho, ou seja, o score da alternativa escolhida pelo estudante.
  