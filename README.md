## Repositório Bootcamp Database Experience DIO

```
Este é o primeiro bootcamp sobre Banco de Dados da DIO para profissionais que procuram uma experiência rápida em Ciência de Dados para se aprimorar nos principais conceitos de banco de dados SQL e NoSQL. No Database Experience você vai passar por 54 horas de imersão, com experiências educacionais e mentorias exclusivas sobre modelagem de dados, SGBD, EER, arquitetura, queries entre outras.
```



**Módulos**:

-  **Módulo - Prepare-se para a jornada**
  -  Curso : Conheça as Oportunidades da DIO
  -  Curso : Seja Protagonista Neste Bootcamp
  -  Curso : Introdução ao Desenvolvimento Moderno de Software
  -  Curso : Introdução ao Git e ao GitHub
  -  Curso : Criando seu Primeiro Repositório no GitHub Para Compartilhar Seu Progresso
  -  Curso : Mentoria (Live) - Database Experience | Aula inaugural - 22/08/2022 ás 19h
-  **Módulo - Banco de Dados SQL**
  -  Curso : Contextualização do Cenário na Área de Banco de Dados
  -  Curso : Explorando a Abordagem de SGBDs
  -  Curso : Overview sobre Modelagem de Dados
  -  Curso : Arquitetura de Bando de Dados
  -  Curso : Fundamentos de Modelagem e Projeto de Banco de Dados
  -  Curso : Explorando o Modelo ER - Entidade Relacionamento
  -  Curso : Modelagem de Dados com EER - Enhanced Entity Relationship
  -  Curso : Refinando um Projeto Conceitual de Banco de Dados - E-COMMERCE
  -  Curso : Construindo um Esquena Conceitual do Zero
  -  Curso : Modelo Relacional e Mapeamento ER/Relacional
  -  Curso : Primeiros Passos com SQL
  -  Curso : Explorando Queries com SQL
  -  Curso : Criando Queries com Funções e Cláusulas de Agrupamentos
  -  Curso : Agrupando Registros e Tabelas com Join Statement
  -  Curso : Construindo seu Primeiro Projeto Lógico de Banco de Dados
  -  Curso : Construa um Projeto Lógico de Banco de Dados do Zero
-  **Tópico - Bancos de Dados NoSQL**
  -  Curso : Introdução ao MongoDB e Bancos de Dados NoSQL
  -  Curso : O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados



## Tecnologias utilizadas nos projetos

<div style="display: inline_block">
<img align="center" alt="git" height="100" width="80" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original-wordmark.svg"/>
<img align="center" alt="GitHub" height="70" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original-wordmark.svg" />
<br>
<h4>Bancos SQL:</h4>    
<img align="center" alt="MySQL" height="100" width="80"  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" />
<img align="center" alt="PostgreSQL" height="100" width="80" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original-wordmark.svg" />
<img align="center" alt="SQL Server" height="100" width="80"  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/microsoftsqlserver/microsoftsqlserver-plain-wordmark.svg" />
<img align="center" alt="SQLite" height="100" width="80"  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original-wordmark.svg" />
<img align="center" alt="Firebird" height="70" width="80"  src="https://firebirdsql.org/file/about/firebird-logo-48.png" />
<br>
<h4>Bancos NoSQL:</h4>    
<img align="left" alt="MongoDB" height="70" width="80"  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original-wordmark.svg" />
<img align="left" alt="Redis" height="70" width="80"  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original-wordmark.svg" />
<img align="left" alt="DynamoDB" height="70" width="110"  src="https://res.cloudinary.com/practicaldev/image/fetch/s--yeQTETna--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ffgjuqw3ijlfz4wf72ha.png" />
<img align="left" alt="Neo4j" height="70" width="110"  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/neo4j/neo4j-original-wordmark.svg" />
<img align="left" alt="Cassandra" height="70" width="110"  src="https://www.vectorlogo.zone/logos/apache_cassandra/apache_cassandra-ar21.svg" />    




​     



## **Desafios:**



- **1-Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE**

```
Objetivo: 

Refinar um modelo de banco de dados apresentado, acrescentando os seguintes pontos:

- Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
- Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
- Entrega – Possui status e código de rastreio;
```



- **2-Construindo um Esquema Conceitual para Banco De dados**

```
Oficina Mecânica:

Objetivo:
Cria o esquema conceitual para o contexto de oficina com base na narrativa fornecida

Narrativa:

- Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica.
- Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas.
- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra.
- O valor de cada peça também irá compor a OS e o cliente autoriza a execução dos serviços.
- A mesma equipe avalia e executa os serviços.
- Os mecânicos possuem código, nome, endereço e especialidade.
- Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.
```

- **3-Construindo seu Primeiro Projeto Lógico de Banco de Dados**

```
Replique a modelagem do projeto lógico de banco de dados para o cenário de e-commerce. Fique atento as definições de chave primária e estrangeira, assim como as constraints presentes no cenário modelado. Perceba que dentro desta modelagem haverá relacionamentos presentes no modelo EER. Sendo assim, consulte como proceder para estes casos. Além disso, aplique o mapeamento de modelos aos refinamentos propostos no módulo de modelagem conceitual.

Assim como demonstrado durante o desafio, realize a criação do Script SQL para criação do esquema do banco de dados. Posteriormente, realize a persistência de dados para realização de testes. Especifique ainda queries mais complexas dos que apresentadas durante a explicação do desafio. Sendo assim, crie queries SQL com as cláusulas abaixo:

Recuperações simples com SELECT Statement
Filtros com WHERE Statement
Crie expressões para gerar atributos derivados
Defina ordenações dos dados com ORDER BY
Condições de filtros aos grupos – HAVING Statement
Crie junções entre tabelas para fornecer uma perspectiva mais complexa dos dados
Diretrizes
Não há um mínimo de queries a serem realizadas;
Os tópicos supracitados devem estar presentes nas queries;
Elabore perguntas que podem ser respondidas pelas consultas;
As cláusulas podem estar presentes em mais de uma query;
O projeto deverá ser adicionado a um repositório do Github para futura avaliação do desafio de projeto. Adicione ao Readme a descrição do projeto lógico para fornecer o contexto sobre seu esquema lógico apresentado.

Objetivo:
Aplique o mapeamento para o  cenário:

“Refine o modelo apresentado acrescentando os seguintes pontos”

Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
Entrega – Possui status e código de rastreio;
Algumas das perguntas que podes fazer para embasar as queries SQL:

Quantos pedidos foram feitos por cada cliente?
Algum vendedor também é fornecedor?
Relação de produtos fornecedores e estoques;
Relação de nomes dos fornecedores e nomes dos produtos;
Agora é a sua vez de ser o protagonista! Implemente o desafio sugerido pela expert e suba seu projeto para um repositório próprio, com isso, você aumentará ainda mais seu portfólio de projetos no GitHub!

CONTEÚDOS
INFORMAÇÕES
Apresentando o Desafio de Projeto Lógico para Banco de Dados
Considerações sobre a Variação Esquema ER
Criando esquema Relacional a partir do Esquema Conceitual
Criando o esquema de Banco de Dados – Script SQL - Parte 1
```



- **4-Construa um Projeto Lógico de Banco de Dados do Zero**

```
Para este cenário você irá utilizar seu esquema conceitual, criado no desafio do módulo de modelagem de BD com modelo ER, para criar o esquema lógico para o contexto de uma oficina. Neste desafio, você definirá todas as etapas. Desde o esquema até a implementação do banco de dados. Sendo assim, neste projeto você será o protagonista. Tenha os mesmos cuidados, apontados no desafio anterior, ao modelar o esquema utilizando o modelo relacional.

Após a criação do esquema lógico, realize a criação do Script SQL para criação do esquema do banco de dados. Posteriormente, realize a persistência de dados para realização de testes. Especifique ainda queries mais complexas do que apresentadas durante a explicação do desafio. Sendo assim, crie queries SQL com as cláusulas abaixo:

Recuperações simples com SELECT Statement;
Filtros com WHERE Statement;
Crie expressões para gerar atributos derivados;
Defina ordenações dos dados com ORDER BY;
Condições de filtros aos grupos – HAVING Statement;
Crie junções entre tabelas para fornecer uma perspectiva mais complexa dos dados;
Diretrizes
Não há um mínimo de queries a serem realizadas;
Os tópicos supracitados devem estar presentes nas queries;
Elabore perguntas que podem ser respondidas pelas consultas
As cláusulas podem estar presentes em mais de uma query

```



- **5-O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados**

```
Neste desafio, você terá a missão de compreender o papel dos Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL) no contexto de um Engenheiro de Dados. Para isso, anote todos os conceitos, definições e insights que julgar relevantes.
```

