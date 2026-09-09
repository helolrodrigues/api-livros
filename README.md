📚 API de Livros

API REST desenvolvida para o gerenciamento de livros, como atividade final do bimestre da disciplina de SW II (Software II) do curso de Informática para Internet.

A aplicação permite realizar operações de cadastro, consulta, atualização e exclusão de livros por meio de endpoints REST.

🎯 Objetivo

O objetivo deste projeto é desenvolver uma API REST para gerenciamento de livros, permitindo realizar operações de CRUD (Create, Read, Update e Delete).

Por meio da API, é possível:

📖 Listar todos os livros cadastrados;
🔎 Consultar um livro específico pelo seu ID;
➕ Cadastrar novos livros;
✏️ Atualizar informações de livros existentes;
🗑️ Remover livros cadastrados.

O projeto foi desenvolvido como parte da atividade final do bimestre da disciplina de SW II.

🔌 Endpoints da API
Método	Endpoint	Descrição
GET	/livros	Lista todos os livros
GET	/livros/{id}	Busca um livro específico pelo ID
POST	/livros	Cadastra um novo livro
PUT	/livros/{id}	Atualiza um livro existente
DELETE	/livros/{id}	Remove um livro
📌 Exemplo de utilização

Para consultar todos os livros cadastrados:

GET /livros


Para consultar um livro específico:

GET /livros/1


Para cadastrar um novo livro:

POST /livros


Para atualizar um livro:

PUT /livros/1


Para excluir um livro:

DELETE /livros/1

🗄️ Banco de Dados

Banco de dados: biblioteca_db

O banco de dados é responsável pelo armazenamento das informações relacionadas aos livros cadastrados na aplicação.

🛠️ Etapas de Desenvolvimento

O desenvolvimento do projeto foi dividido em 4 etapas, acompanhando a evolução da aplicação durante a atividade.

Etapa 1 — Configuração Inicial
Estrutura inicial do projeto;
Configuração do ambiente de desenvolvimento;
Criação da base da aplicação;
Configuração inicial do banco de dados.

Commit: commit 1 — Configuração inicial

Etapa 2 — Estrutura da API
Criação da estrutura de rotas;
Implementação dos primeiros endpoints;
Organização dos arquivos e componentes da aplicação.

Commit: commit 2 — Desenvolvimento da estrutura da API

Etapa 3 — Operações CRUD
Implementação das operações de cadastro;
Consulta de livros;
Atualização de registros;
Exclusão de livros.

Commit: commit 3 — Implementação das operações CRUD

Etapa 4 — Finalização e Testes
Testes dos endpoints;
Correção de erros;
Ajustes finais na aplicação;
Organização e documentação do projeto.

Commit: commit 4 — Finalização e testes

📊 Histórico de Commits
Etapa	Commit	Descrição
1	commit 1	Configuração inicial
2	commit 2	Desenvolvimento da estrutura da API
3	commit 3	Implementação das operações CRUD
4	commit 4	Finalização e testes
👩‍💻 Informações Acadêmicas
Informação	Detalhes
Aluna	Heloísa Lima Rodrigues
Curso	Informática para Internet
Disciplina	SW II
Professor(a)	Anderson Vanin
Instituição	Etec MCM
Ano	2026
📌 Considerações Finais

Este projeto foi desenvolvido com o objetivo de aplicar, na prática, os conceitos estudados na disciplina de SW II, especialmente relacionados ao desenvolvimento de APIs REST, gerenciamento de dados e implementação de operações CRUD.

O desenvolvimento também proporcionou a prática de organização de projetos, utilização de banco de dados e controle da evolução da aplicação por meio de commits.
