# 🤖 AI-LAB

Laboratório pessoal para estudo, desenvolvimento e experimentação com Inteligência Artificial, Automação, Docker e Business Analysis.

O objetivo deste projeto é criar um ambiente local, modular e reproduzível para desenvolver soluções utilizando IA Generativa, automações, bancos de dados e ferramentas modernas de desenvolvimento.

---

# 🎯 Objetivos

* Aprender Docker e Docker Compose na prática
* Desenvolver automações utilizando n8n
* Trabalhar com PostgreSQL
* Estudar Inteligência Artificial Generativa
* Criar agentes de IA
* Construir projetos de portfólio
* Consolidar conhecimentos para retorno à área de TI

---

# 🏗 Arquitetura Atual

```
                     Docker Desktop
                            │
                    docker-compose.yml
                            │
        ┌───────────────────┼───────────────────┐
        │                   │                   │
        ▼                   ▼                   ▼
   PostgreSQL             n8n              pgAdmin
        │
        └──────── Banco de Dados ───────────────┘
```

---

# 📦 Tecnologias

* Docker Desktop
* Docker Compose
* PostgreSQL 16
* n8n
* pgAdmin 4
* Git
* GitHub

Tecnologias planejadas:

* Ollama
* Open WebUI
* Qdrant
* Redis
* Modelos LLM locais
* APIs de IA

---

# 📂 Estrutura do Projeto

```
AI-LAB/
│
├── .env
├── .env.example
├── .gitignore
├── docker-compose.yml
├── README.md
│
├── Assets/
├── Docker/
├── Documentacao/
├── Projetos/
├── Prompts/
└── n8n/
```

---

# ⚙️ Pré-requisitos

* Docker Desktop instalado
* Git instalado
* Git Bash
* VS Code (recomendado)

---

# 🚀 Como executar

Subir os containers:

```bash
docker compose up -d
```

Parar os containers:

```bash
docker compose down
```

Visualizar containers ativos:

```bash
docker ps
```

Visualizar logs:

```bash
docker compose logs
```

---

# 🌐 Serviços Disponíveis

| Serviço    | URL                   | Porta |
| ---------- | --------------------- | ----: |
| n8n        | http://localhost:5678 |  5678 |
| pgAdmin    | http://localhost:8080 |  8080 |
| PostgreSQL | localhost             |  5432 |

---

# 🔐 Configuração

As configurações sensíveis ficam no arquivo:

```
.env
```

O arquivo:

```
.env.example
```

serve como modelo para criação de novos ambientes.

---

# 📚 O que já foi implementado

* Docker configurado
* Docker Compose configurado
* PostgreSQL integrado
* pgAdmin configurado
* n8n configurado
* Persistência de dados com volumes
* Variáveis de ambiente (.env)
* .gitignore
* .env.example
* Primeiro workflow no n8n executado com sucesso

---

# 🧪 Projetos Planejados

* Agente para Business Analysis
* Gerador de User Stories
* Gerador de Casos de Teste
* Assistente SQL
* Assistente para documentação técnica
* Integração com modelos locais de IA
* RAG utilizando banco vetorial

---

# 🗺 Roadmap

## Fase 1 — Infraestrutura

* [x] Docker
* [x] Docker Compose
* [x] PostgreSQL
* [x] pgAdmin
* [x] n8n
* [x] Variáveis de ambiente
* [x] Git

## Fase 2 — Automação

* [ ] Webhooks
* [ ] PostgreSQL no n8n
* [ ] APIs REST
* [ ] Workflows avançados

## Fase 3 — IA Local

* [ ] Ollama
* [ ] Open WebUI
* [ ] Integração com n8n

## Fase 4 — Banco Vetorial

* [ ] Qdrant
* [ ] RAG

## Fase 5 — Portfólio

* [ ] Projetos completos
* [ ] Publicação no GitHub

---

# 📖 Aprendizados

Este laboratório documenta a evolução prática no uso de:

* Docker
* Containers
* Docker Compose
* Automação
* PostgreSQL
* Inteligência Artificial
* Business Analysis
* Git

---

# 📄 Licença

Projeto criado para fins de estudo, pesquisa e desenvolvimento de soluções utilizando Inteligência Artificial e automação.
