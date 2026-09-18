# 📚 API de Livros

API REST desenvolvida como atividade final do bimestre da disciplina de **Sistemas Web II (SW II)** do curso de **Informática para Internet** da Etec Professora Maria Cristina Medeiros.

O projeto tem como objetivo desenvolver uma API para o **gerenciamento de livros**, utilizando operações CRUD e integração com banco de dados.

> 🚧 **Status do projeto: Etapa 3 de 4 em desenvolvimento**

---

## 🎯 Objetivo do Projeto

O objetivo da aplicação é permitir o gerenciamento de livros por meio de uma API REST.

A API utiliza os princípios de **CRUD**, permitindo realizar quatro operações principais:

* 🟢 **Create** → cadastrar novos livros;
* 🔵 **Read** → consultar livros cadastrados;
* 🟡 **Update** → atualizar informações de livros;
* 🔴 **Delete** → excluir livros.

Dessa forma, a aplicação permite que os dados sejam manipulados por meio de requisições HTTP.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido utilizando:

* 🐍 **Python**
* ⚡ **FastAPI**
* 🗄️ **MySQL**
* 🔗 **SQLAlchemy**
* 🚀 **Uvicorn**
* 🧪 **Pytest**
* 🖥️ **Visual Studio Code**
* 📦 **Git e GitHub**

---

## 📂 Estrutura do Projeto

A aplicação é organizada em diferentes arquivos, separando as responsabilidades de cada parte do sistema.

```text
api-livros/
│
├── app/
│   ├── main.py
│   ├── database.py
│   ├── models.py
│   └── schemas.py
│
├── tests/
│   └── test_livros.py
│
├── requirements.txt
└── README.md
```


---

# 🔌 Endpoints da API

Atualmente, a API possui as seguintes rotas para gerenciamento de livros:

| Método   | Endpoint       | Descrição                         |
| -------- | -------------- | --------------------------------- |
| `GET`    | `/livros`      | Lista todos os livros cadastrados |
| `GET`    | `/livros/{id}` | Busca um livro específico pelo ID |
| `POST`   | `/livros`      | Cadastra um novo livro            |
| `PUT`    | `/livros/{id}` | Atualiza um livro existente       |
| `DELETE` | `/livros/{id}` | Remove um livro cadastrado        |

---

## 📖 Exemplos de Utilização

### 🔎 Listar todos os livros

```http
GET /livros
```

Retorna todos os livros cadastrados no banco de dados.

---

### 🔎 Buscar um livro pelo ID

```http
GET /livros/1
```

Busca o livro que possui o ID informado.

---

### ➕ Cadastrar um livro

```http
POST /livros
```

Exemplo de dados enviados:

```json
{
    "titulo": "Dom Casmurro",
    "autor": "Machado de Assis",
    "ano": 1899
}
```

---

### ✏️ Atualizar um livro

```http
PUT /livros/1
```

Permite alterar as informações de um livro já cadastrado.

---

### 🗑️ Excluir um livro

```http
DELETE /livros/1
```

Remove o livro correspondente ao ID informado.

---

# 📊 Operações CRUD

O funcionamento da API pode ser representado da seguinte forma:

```text
              📚 API DE LIVROS
                     │
        ┌────────────┼────────────┐
        │            │            │
      CREATE        READ        UPDATE
        │            │            │
       POST       GET /livros     PUT
        │            │            │
        └────────────┼────────────┘
                     │
                   DELETE
                     │
                  DELETE
```

As operações são realizadas por meio dos métodos HTTP correspondentes, permitindo a comunicação entre a aplicação e o banco de dados.

---

# 🗄️ Banco de Dados

O projeto utiliza o **MySQL** para armazenar os dados dos livros.

### Banco utilizado

```text
biblioteca_db
```

O banco de dados é responsável por armazenar os registros cadastrados pela API, permitindo que as informações permaneçam salvas mesmo após o encerramento da aplicação.

A comunicação entre a API e o banco de dados é realizada utilizando **SQLAlchemy**.

---

# 🚧 Etapas de Desenvolvimento

O desenvolvimento da API foi dividido em **4 etapas**, acompanhando a evolução do projeto durante a atividade.

## ✅ Etapa 1 — Configuração Inicial

Nesta primeira etapa foram realizadas as configurações básicas necessárias para iniciar o projeto.

* Criação da estrutura inicial;
* Configuração do ambiente Python;
* Instalação das dependências;
* Configuração inicial do FastAPI;
* Configuração inicial do banco de dados.

**Commit:** `commit 1 — Configuração inicial`

---

## ✅ Etapa 2 — Estrutura da API

Na segunda etapa foi criada a estrutura principal da API.

* Criação das rotas;
* Organização dos arquivos;
* Criação dos modelos;
* Criação dos schemas;
* Implementação dos primeiros endpoints;
* Integração inicial com o banco de dados.

**Commit:** `commit 2 — Desenvolvimento da estrutura da API`

---

## 🔄 Etapa 3 — Operações CRUD

### 📍 Etapa atual

Atualmente, o projeto está na **Etapa 3**, responsável pela implementação das operações CRUD.

Nesta etapa estão sendo desenvolvidas e testadas as funcionalidades de:

* ➕ Cadastro de livros;
* 📖 Consulta de livros;
* 🔎 Consulta de livro por ID;
* ✏️ Atualização de livros;
* 🗑️ Exclusão de livros;
* 🔗 Comunicação das operações com o banco de dados.

**Commit:** `commit 3 — Implementação das operações CRUD`

> 🛠️ **Status: Em desenvolvimento**

---

## ⏳ Etapa 4 — Finalização e Testes

A quarta etapa será realizada após a conclusão das operações CRUD.

Está prevista a realização de:

* 🧪 Testes das rotas;
* 🔍 Verificação do funcionamento da API;
* 🐛 Correção de possíveis erros;
* 📋 Elaboração dos relatórios de testes;
* ✨ Ajustes finais;
* 📚 Organização da documentação;
* 🚀 Finalização do projeto.

**Commit previsto:** `commit 4 — Finalização e testes`

> ⏳ **Status: Ainda não iniciada**

---

# 📈 Progresso do Projeto

| Etapa       | Status          | Descrição            |
| ----------- | --------------- | -------------------- |
| 1️⃣ Etapa 1 | ✅ Concluída     | Configuração inicial |
| 2️⃣ Etapa 2 | ✅ Concluída     | Estrutura da API     |
| 3️⃣ Etapa 3 | 🔄 Em andamento | Operações CRUD       |
| 4️⃣ Etapa 4 | ⏳ Pendente      | Finalização e testes |


**🟡 Projeto em desenvolvimento**

---

# 🧪 Testes

A aplicação também contará com testes automatizados utilizando **Pytest**.

Os testes têm como objetivo verificar se as rotas da API estão funcionando corretamente e se as operações realizadas retornam os resultados esperados.

A etapa de testes será concluída durante a **Etapa 4**.

---

# 🚀 Como Executar o Projeto

### 1. Clonar o repositório

```bash
git clone URL_DO_REPOSITORIO
```

### 2. Entrar na pasta do projeto

```bash
cd api-livros
```

### 3. Criar o ambiente virtual

```bash
python -m venv .venv
```

### 4. Ativar o ambiente virtual

No Windows:

```bash
.venv\Scripts\activate
```

### 5. Instalar as dependências

```bash
pip install -r requirements.txt
```

### 6. Iniciar a API

```bash
python -m uvicorn app.main:app --reload
```

---

# 👩‍💻 Informações Acadêmicas

| Informação      | Detalhes                                |
| --------------- | --------------------------------------- |
| 👩‍🎓 Aluna     | Heloísa Lima Rodrigues                  |
| 💻 Curso        | Informática para Internet               |
| 📚 Disciplina   | Sistemas Web II (SW II)                 |
| 👨‍🏫 Professor | Anderson Vanin                          |
| 🏫 Instituição  | Etec Professora Maria Cristina Medeiros |
| 📅 Ano          | 2026                                    |

---

# 📌 Considerações Finais

O projeto **API de Livros** está sendo desenvolvido com o objetivo de aplicar, na prática, os conhecimentos adquiridos na disciplina de **Sistemas Web II**.

Durante o desenvolvimento, estão sendo trabalhados conceitos relacionados à criação de APIs REST, desenvolvimento com FastAPI, integração com banco de dados, operações CRUD, organização de projetos e controle de versões utilizando Git e GitHub.

Atualmente, o projeto encontra-se na **Etapa 3 de desenvolvimento**, com foco na implementação das operações de cadastro, consulta, atualização e exclusão de livros.

As etapas seguintes serão responsáveis pela realização dos testes, correções, documentação e finalização da aplicação.

---

📚 **API de Livros | SW II | Etec MCM | 2026**
