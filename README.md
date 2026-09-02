📚 API de Livros

Uma breve descrição explicando que o projeto consiste em uma API REST para gerenciamento de livros, desenvolvida como atividade final do bimestre da disciplina de SW II.

🎯 Objetivo

Explique de forma clara o objetivo da aplicação, mencionando que ela permite realizar operações relacionadas ao cadastro e gerenciamento de livros por meio de uma API.

🛠️ Tecnologias utilizadas

Crie uma lista ou tabela apresentando as principais tecnologias:

Tecnologia	Utilização
Python	Linguagem principal
FastAPI	Desenvolvimento da API
MySQL	Banco de dados
SQLAlchemy	Comunicação com o banco
Pydantic	Validação e schemas
Swagger/OpenAPI	Documentação e testes da API
Git/GitHub	Versionamento do projeto
🏗️ Estrutura do projeto

Mostre uma estrutura de pastas/arquivos em formato de árvore, por exemplo:

API-Livros/
│
├── main.py
├── models.py
├── schemas.py
├── database.py
├── requirements.txt
└── README.md

🔌 Endpoints da API


Método	Endpoint	Descrição
GET	/livros	Lista todos os livros
GET	/livros/{id}	Busca um livro específico
POST	/livros	Cadastra um novo livro
PUT	/livros/{id}	Atualiza um livro
DELETE	/livros/{id}	Remove um livro



⚙️ Como executar o projeto

Crie um passo a passo para executar a API localmente:

Clonar o repositório.
Entrar na pasta do projeto.
Criar/ativar um ambiente virtual, se necessário.
Instalar as dependências.
Configurar o banco de dados MySQL.
Configurar a conexão do projeto com o banco.
Executar a aplicação FastAPI.
Acessar o Swagger.

Use comandos genéricos e corretos, por exemplo:

git clone URL_DO_REPOSITORIO
cd NOME_DO_PROJETO

pip install -r requirements.txt

uvicorn main:app --reload

Não invente informações específicas de banco, usuário ou senha. Utilize placeholders quando necessário.

🗄️ Banco de dados

Explique que o projeto utiliza MySQL para armazenar os dados dos livros.

Inclua um espaço para o nome do banco:

Banco de dados: [NOME_DO_BANCO]

Explique brevemente a função do SQLAlchemy na comunicação entre a aplicação e o banco de dados.

🧪 Testes

Explique que os endpoints podem ser testados diretamente pelo Swagger, permitindo verificar as operações de cadastro, consulta, atualização e exclusão dos livros.

📌 Requisitos da atividade

Crie uma seção destacando os requisitos cumpridos:

API desenvolvida com FastAPI

Integração com MySQL

Utilização de Models

Utilização de Schemas

Endpoints CRUD

Documentação pelo Swagger/OpenAPI

Versionamento com Git

Mínimo de 4 commits

4 etapas de desenvolvimento

📊 Histórico de commits

Crie uma tabela para registrar os commits:

Etapa	Commit	Descrição
1	commit 1	Configuração inicial
2	commit 2	Configuração do banco
3	commit 3	Models, schemas e endpoints
4	commit 4	Swagger, testes e finalização

Deixe os nomes dos commits como placeholders para que possam ser substituídos pelos commits reais do GitHub.

🎓 Sobre o projeto

Finalize explicando que este projeto foi desenvolvido como atividade final do bimestre da disciplina de SW II, com o objetivo de aplicar na prática os conhecimentos de desenvolvimento de APIs, integração com banco de dados, validação de dados, documentação e versionamento.

Inclua espaços para:

Aluno(a): [SEU NOME]
Curso: Informática para Internet
Disciplina: SW II
Professor(a): [NOME DO PROFESSOR]
Instituição: Etec [NOME DA ETEC]
Ano: 2026

Estilo do README
Use Markdown corretamente.
Utilize emojis apenas nos títulos para deixar o README visualmente agradável, sem exagerar.
Use tabelas quando ajudarem na organização.
Use blocos de código para comandos, JSON e estrutura de pastas.
Mantenha uma aparência profissional e acadêmica.
Não deixe o README excessivamente longo.
Não invente funcionalidades que não foram mencionadas.
Onde faltarem informações específicas do projeto, use [PREENCHER] ou [SUBSTITUIR].
Dê bastante destaque à evolução em 4 etapas e aos 4 commits obrigatórios, pois esse é um dos requisitos principais da atividade.
O resultado deve parecer um README real de um projeto publicado no GitHub, e não um texto genérico de tutorial.