# compass
DESAFIO SPRINT 1

RESPOSTAS DO QUESTIONÁRIO DO DESAFIO:

Perguntas: 

1- Para que serve o método Scrum? 

O Scrum é framework ágil para se gerenciar projetos complexos com mais agilidade, maior feedback ao cliente, comprometimento e uniao da equipe, revisao do que pode ser melhorado e do que foi implementado de forma certeira no projeto, eliminando o método waterfall e seu modelo em cascata. O Scrum se organiza em ciclos que se repetem. Tem como pilares a transparencia, a inspeçao e a adaptaçao.



2- Como funciona o método Scrum? 

O scrum está organizado em ciclos, que como foi dito acima, se repetem. Esses ciclos chamam-se "sprints" (corrida em tiro, em ingles). Os sprints sao formados por time boxes, que sao "caixinhas de tempo" ou "pacotes inflexíveis", ou seja, nao podemos mudar o tempo de uma time box. Os sprints duram duas semanas e tem várias cerimonias: Planning, Desenvolvimento, Review e Restrospective. Após essas fases, o ciclo volta se repete com as mesmas fases, de acordo com as atividades e previsoes do projeto. No planejamento, planeja-se, é claro, as atividades da sprint, durando 5% do tempo total, e organizam-se as prioridade com o product backlog (ítens técnicos para a equipe) através da negociaçao do que cada um pode fazer e o que fará. No product backlog, todos opinam, mas quem decide é o P.O (Product Owner) No desenvolvimento, existem as daily reviews, que duram até 15 minutos e sao realizadas diariamente, em que cada membro do time responderá as perguntas: o que fiz desde a última Daily review? O que estou fazendo? O que farei até amanha? O desenvolvimento é quando, coloquialmente, se coloca "a mao na massa" e se desenvolve o produto ou atividades até que estejam prontas. Depois do produto passar por testes, homologaçoes e estar considerado pronto, é feita uma review meeting, com o cliente e o time, que toma o total de 2,5% do tempo da sprint. Nela o cliente observa os ítens prontos e pode testar o produto sem que lhe sejam fornecidas instruçoes e pode fornecer o feedback. Logo depois da review, é realizada a retrospective, em que podem ser utilizadas algumas técnicas como o Kanban, por exemplo. Toma cerca de 5% do sprint e tem como participantes o scrum master, os deenvolvedores e o product owner. Inicia-se pela prime directive, diretriz que prega que, nao importa o que tenha acontecido durante a sprint, todos fizeram seu melhor para atingir seus objetivos. Serve para mostrar pontos positivos e negativos, sempre com o intuito de aprimorar o andamento do projeto. No scrum, os principais atores sao os desenvolvedores (os que desenvolvem o produto, botam "a mao na massa"), o Product Owner, que faz principalmente a ponte entre o cliente e os desenvolvedores e também facilita o trabalho dos desenvolvedores. Embora os desenvolvedores nao estejam proibidos de conversar com o cliente, é de melhor organizaçao que esta tarefa seja feita por uma pessoa só, a fim de evitar discrepancias e o scrum master, que é o responsável por transmitir os valores do framework scrum à equipe, como um educador. Ele é responsável por potencializar e juntamente com o PO facilitar o trabalho da equipe, sendo o SM responsável pela compreensao da metodologia utilizada, dirimir dúvidas e resolver eventuais problemas quando o P.O. nao consegue resolver, por exemplo, o "sumiço" de um cliente.



3- O que é Git? 

O git é um sistema de controle de versoes compartilhadas. Com ele, é mais fácil de se trabalhar em equipe, onde várias pessoas contribuem simultaneamente, uma vez que as alteraçoes (criar e editar arquivos) nos códigos sao compartilhadas e avisadas aos outros membros da equipe, Quando se disponibiliza um arquivo no git, ele guarda um histórico, pois se houver algum problema pode-se desfazer o que foi feito.



4- O que é um scrum Product Owner? 

O Product Owner, no scrum, é um facilitador da equipe junto ao cliente, além de priorizar as atividades que estao no Product Backlog da equipe.




5- Qual o comando para criação de um novo repositório no Git?

git init



6- O que é o HTTP? 

O HTTP (Protocolo de Transferência de Hipertexto) é um protocolo que define as regras de comunicaçao entre o servidor e o cliente. É o protocolo mais importante da internet. Pode ser utilizado também em mobile. Todo protocolo utiliza-se de uma url como caminho para um recurso, Ex: http://www.euteamo.com.br, sendo http:// o protocolo e o www.euteamo.com.br o domínio. Também pode ser feita a comunicaçao através de um IP, porém a versao em URL é mais amigável, mais comercial e mais fácil de ser gravada. O domínio compoe-se de subdomínios, que sao as partes do domínio, como euteamo, top level domain (br). Todo protocolo HTTP faz uma requisiçao através de um método ao servidor, quando se dirige a um endereço específico neste, e recebe uma resposta em forma de cabeçalho. No cabeçalho, geralmente estao todas as informaçoes desta requisiçao. Existe também o protocolo HTTPS, que é a versao segura e criptografada do HTTP, já que este trabalha com texto puro.



7- Como funciona o HTTP? 

Como já foi dito anteriormente, o usuário digita uma url ou numero de IP a fim de gerar uma requisiçao para um recurso no servidor, que é recebida através de texto puro, e retorna com um cabeçalho, indicando onde está aquele domínio ou IP. Cada requisiçao é única,o que chamamos de stateless, e para cada resposta, deve ser feita uma requisiçao. A requisiçao pode ser representada através métodos como GET, HOST, USER-AGENT, ACCEPT, ACCEPT LANGUAGE e ACCEPT ENCODING. A cada requisiçao ao servidor, o protocolo devolve uma resposta ao cliente, com um código, que pode se escrever na forma de 200 (Deu tudo certo!), 300 (moved), 400 (not found, o mais indesejável), 500 (internet server error). Os cabeçalhos também sao utilizados para especificar as representaçoes (como JSON, XML...). Já existe o HTTP2, que possui a propriedade de header stateful, isto é, faz apenas uma request e recebe respostas, em vez de realizar uma request para cada elemento da página, otimizando o tempo de navegaçao e fazendo o usuário muito mais feliz.



8- Com o Git Você pode propor mudanças (adicioná-las ao Index) usando um comando. Qual é esse comando? 

git commit



9- O que é a Branch master e para que serve?

As branches sao locais onde se quer alterar os arquivos. Servem para que altere partes de um arquivo, sem precisar modificá-lo totalmente. Quando se cria um repositório, ele primeiro surge com a branch master, que é como se fosse o tronco de uma árvore de todos os outros ramos (branches) que serao criados. É basicamente o primeiro lugar para onde apontam os locais onde serao feitos os commits (branches secundárias). 



10- Quais são os comandos usados para atualizar um repositório local e fazer merge de um outro branch ao seu branch ativo?

Atualizar um repositório local-  git add local (endereço da pasta). O merge de duas branches pode ser feito com o comando git merge *nome da branch*



11- Pensando em Bases de dados, sendo elas, Relacionais (SQL) e Não Relacionais (NoSQL). Quais alternativas abaixo estão corretas? 

MySQL = MongoDB 

PostgreSQL = Redis 

Oracle = CouchDB 

Todas as alternativas estão corretas. x



12- O que é MongoDB? 

O MongoDB é um sistema de banco de dados nao relacional, que trabalha com documentos ao invés de tabelas e linhas.



13- O que é o MySQL?

O MySQL é um banco de dados que pode ser acessado para adiçoes, consultas, modificaçoes, com criaçao de tabelas, com colunas e linhas. É muito útil, pois está limitado ao hardware utilizado.



14- Qual a diferença entre git e github? 

O git é um sistema de controle de versao de arquivos, em que se pode fazer alteraçoes de adiçoes e ediçao de arquivos, trabalhando em equipe e tendo um histórico do que foi alterado. Já o github é uma plataforma, onde voce pode criar um repositório público ou privado e inserir seu código, em que se há a disponibilidade de outros desenvolvedores visualizá-los. É como se fosse uma rede social de arquivos. 



15- Quais os dois verbos http que podemos utiizar para realizar um update? Explique a diferença entre eles.

PUT e POST
PUT atuliza todos os dados do recurso, e cria algo
POST também pode modificar arquivos. Usando o POST, o navegador envia os dados do formulário no corpo da requisição e não na URL.



16- Qual o status code que pode ser usado na criação de um novo usuário?

POST request



17- Quais são os três status code que modem ser utilizados para realizar o delete? 

202 (aceito)

204 (nao-aceito)

200 (ok) 



18- Qual a extensão ".xxx" contêm as definições da tabela?

Commands.myi 

Commands.frm 

Commands.myd x

{mysqlDirectory}/data 



19- A pasta "C:\ProgramData" é uma pasta oculta, portanto, você deve digitá-la no endereço do Windows Explorer para chegar lá.  
Nessa pasta de dados, quais opções apresentam o caminho correto para acessar os bancos de dados que foram denominados? 

/{database_name_folder}/{database_tables_and_files}. 

C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.frm 

C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.ibd x

C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\data-recovery 



20- Qual a extensão ".xxx" que contêm os dados da tabela?

.sql



21- Qual comando usa-se para extração de arquivos em MongoDB durante a instalação? 

Em MAC e Linux a extraçao é feita pelo comando 'tar"



22- Para que usamos o MongoDB?

Um dos usos que aparece bastante no MongoDB é a busca por proximidade. O MongoDB trabalha com documentos, ao contrário de tabelas e linhas, como os bancos de dados tradicionais, oferecendo agilidade. Tem baixo custo, por ser de licença free, pode ser utilizado por empresas pequenas e permite executar consultas utilizando o javascript. Tem grande flexibilidade, devido a seu banco de dados que nao segue nenhum esquema, tem alta disponibilidade para os acessos, projetos que envolvem Big Data e uma boa documentaçao oficial, que pode ser utilizada para melhorar as operaçoes.



23- Exemplifique para que serve os metódos http 1xx, 2xx, 3xx, 4xx e 5xx. De uma forma macro (geral)!

Os códigos do HTML tem 3 dígitos, sendo que o primeiro serve para identificar a resposta do servidor.
2XX- successful responses - quando a url é acessada com sucesso no servidor
3XX- Redirection messages - quando o endereço foi movido ou redirecionado
4XX- Cliente error responses - quando uma url ou IP nao existem, no caso nao encontrados
5XX - Server error responses - erro na resposta do servidor



Conta pra gente como foi sua experiência na Sprint#01 do programa de bolsa

Eu adorei, aprendi muito, achei um pouco corrido mas aprendi até a me acostumar com a corrida, fiz os cursos, anotei tudo, me interessei pelos estudos. Enfim, estou muito, muito feliz por ter chegado até aqui e ter conseguido aprender e fazer tudo isso, creio que a cada sprint comemoraremos nossas lindas vitórias, nossa perseverança, dificuldades e facilidade como um time. Cada vez ficaremos mais juntos, mais afetivos ao trabalho e é isso que busco, antes de tudo, um trabalho afetivo e ser feliz fazendo algo que estou AMANDO e sei que tenho potencial para alcançar. Hoje melhor do que ontem, menos do que amanha. Muito feliz e realizada.Muito obrigada pela oportunidade de crescimento.
