<!-- Este README foi preenchido a partir do template acadêmico solicitado para o projeto HubArena. -->
<!-- As tecnologias, links, ambientes e comandos descritos são fictícios e têm finalidade de documentação/projeto. -->

<!-- [![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=99999999&assignment_repo_type=AssignmentRepo) [![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=99999999)
-->

<a href="https://classroom.github.com/online_ide?assignment_repo_id=99999999&assignment_repo_type=AssignmentRepo"><img src="https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg" width="200"/></a> <a href="https://classroom.github.com/open-in-codespaces?assignment_repo_id=99999999"><img src="https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg" width="250"/></a>

---

# 🏟️ HubArena 👨‍💻

> [!NOTE]
> O **HubArena** é uma plataforma para **reserva e gestão de quadras esportivas**, permitindo que clientes consultem arenas, visualizem quadras disponíveis, solicitem reservas e acompanhem o status das solicitações. Prestadores podem cadastrar arenas, administrar quadras e aceitar ou recusar pedidos de reserva.

<table>
  <tr>
    <td width="800px">
      <div align="justify">
        O <b>HubArena</b> foi projetado como uma aplicação acadêmica voltada à organização de reservas esportivas. 
        A solução centraliza o cadastro de arenas, quadras, clientes, prestadores e reservas, reduzindo conflitos de horário 
        e melhorando a comunicação entre usuários e responsáveis pelos espaços esportivos. O projeto utiliza documentação em 
        <b>Markdown</b>, modelagem UML em <b>PlantUML</b> e uma arquitetura fictícia, porém realista, baseada em 
        front-end web, API REST, banco de dados relacional, mensageria e serviço de notificações.
      </div>
    </td>
    <td>
      <div>
        <img src="https://joaopauloaramuni.github.io/image/logo_ES_vertical.png" alt="Logo do Projeto" width="120px"/>
      </div>
    </td>
  </tr> 
</table>

---

## 🚧 Status do Projeto

### Badges básicos:

[![Status](https://img.shields.io/badge/Status-Documentado-007ec6)](#)
[![Versão](https://img.shields.io/badge/Versão-v1.0.0-blue)](#)
[![Licença](https://img.shields.io/badge/Licença-MIT-green)](#licença)
[![PlantUML](https://img.shields.io/badge/PlantUML-UML-orange)](https://plantuml.com/)
[![Documentação](https://img.shields.io/badge/Documentação-Concluída-brightgreen)](#documentações-utilizadas)

### Outros badges:

![React](https://img.shields.io/badge/React-19.1.1-007ec6?style=for-the-badge&logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7.1.2-007ec6?style=for-the-badge&logo=vite&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-007ec6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.12-007ec6?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-3.0-007ec6?style=for-the-badge&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-007ec6?style=for-the-badge&logo=postgresql&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-3.13-007ec6?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-007ec6?style=for-the-badge&logo=docker&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-API_Testing-007ec6?style=for-the-badge&logo=postman&logoColor=white)

> [!IMPORTANT]
> Projeto documentado para fins acadêmicos. Não é obrigatória a implementação completa do código-fonte, pois o foco do trabalho é a modelagem, arquitetura e diagramação da aplicação.

---

## 📚 Índice
- [Links Úteis](#-links-úteis)
- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades Principais](#-funcionalidades-principais)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Arquitetura](#-arquitetura)
  - [Exemplos de diagramas](#exemplos-de-diagramas)
- [Instalação e Execução](#-instalação-e-execução)
  - [Pré-requisitos](#pré-requisitos)
  - [Variáveis de Ambiente](#-variáveis-de-ambiente)
     - [1 Back-end Flask](#1-back-end-flask)
     - [2 Front-end React, Vite](#2-front-end-react-vite)
     - [3 Exemplos de Variáveis de Ambiente na Vercel](#3-exemplos-de-variáveis-de-ambiente-na-vercel)
  - [Instalação de Dependências](#-instalação-de-dependências)
    - [Front-end React](#front-end-react)
    - [Back-end Flask](#back-end-flask)
  - [Inicialização do Banco de Dados PostgreSQL](#-inicialização-do-banco-de-dados-postgresql)
  - [Como Executar a Aplicação](#-como-executar-a-aplicação)
    - [Terminal 1: Back-end Flask](#terminal-1-back-end-flask)
    - [Terminal 2: Front-end React, Vite](#terminal-2-front-end-react-vite)
    - [Execução Local Completa com Docker Compose Incluindo Banco de Dados](#-execução-local-completa-com-docker-compose-incluindo-banco-de-dados)
    - [Passos para build, inicialização e execução](#-passos-para-build-inicialização-e-execução)
- [Deploy](#-deploy)
- [Estrutura de Pastas](#-estrutura-de-pastas)
- [Demonstração](#-demonstração)
  - [Aplicativo Mobile](#-aplicativo-mobile)
  - [Aplicação Web](#-aplicação-web)
  - [Exemplo de saída no Terminal para Back-end, API, CLI](#-exemplo-de-saída-no-terminal-para-back-end-api-cli)
- [Testes](#-testes)
- [Documentações utilizadas](#-documentações-utilizadas)
- [Autores](#-autores)
- [Contribuição](#-contribuição)
- [Agradecimentos](#-agradecimentos)
- [Licença](#-licença)

---

## 🔗 Links Úteis
* 🌐 **Demo Online:** [Acesse a Aplicação Web](https://hubarena-demo.vercel.app)
  > 💻 **Descrição:** Link fictício para a aplicação web em ambiente de produção, hospedada em plataforma como Vercel ou Netlify.
* 📱 **Download Mobile:** [Google Play](https://play.google.com/store/apps/details?id=br.com.hubarena.app) | [APK Direto](https://hubarena-demo.vercel.app/download/hubarena.apk)
  > 📱 **Descrição:** Links fictícios para download do aplicativo móvel do HubArena.
* 📖 **Documentação:** [Leia a Wiki/Docs](./docs/HubArena_Documentacao_de_Projeto.pdf)
  > 📚 **Descrição:** Acesso à documentação técnica completa do projeto, contendo diagramas UML, descrição de atores, casos de uso, arquitetura, componentes, implantação, classes, estados e modelo de dados.
* 🧩 **Diagramas PlantUML:** [Pasta de Diagramas](./docs/plantuml)
  > 🧩 **Descrição:** Pasta fictícia contendo os arquivos `.puml` utilizados para gerar os diagramas do projeto.
* 🧪 **Collection Postman:** [HubArena API Collection](./docs/postman/HubArena.postman_collection.json)
  > 🧪 **Descrição:** Collection fictícia para validação dos endpoints REST da aplicação.

---

## 📝 Sobre o Projeto
O **HubArena** é um sistema projetado para facilitar a **reserva e a gestão de quadras esportivas**. A aplicação permite que clientes encontrem arenas, consultem quadras disponíveis, solicitem reservas e acompanhem o status dessas solicitações. Também permite que prestadores cadastrem arenas, administrem quadras, definam disponibilidade e analisem pedidos de reserva.

O projeto existe para resolver um problema comum em ambientes esportivos: a dificuldade de organizar horários, evitar reservas duplicadas e manter uma comunicação clara entre clientes e responsáveis pelas quadras. Em muitos locais, esse controle é feito por telefone, mensagens ou planilhas, o que pode gerar conflitos de horário, perda de registros e baixa rastreabilidade.

O contexto do projeto é acadêmico, sendo elaborado como parte da disciplina **Projeto de Software**. Seu objetivo principal é demonstrar a capacidade de projetar uma aplicação por meio de documentação técnica, arquitetura, regras de negócio e diagramas UML produzidos com **PlantUML**.

O sistema pode ser utilizado em cenários reais ou simulados, como clubes, arenas de futebol society, escolas esportivas, quadras poliesportivas, condomínios, centros de treinamento e espaços privados destinados à locação esportiva.

> [!NOTE]
> O HubArena foi documentado considerando tecnologias fictícias, mas compatíveis com uma aplicação real baseada em API REST, banco de dados relacional e mensageria assíncrona.

---

## ✨ Funcionalidades Principais
- 🔐 **Autenticação de Usuários:** cadastro e login de clientes, prestadores e administradores.
- 👤 **Gerenciamento de Usuários:** criação, consulta e controle dos perfis do sistema.
- 🏟️ **Cadastro de Arenas:** prestadores podem cadastrar arenas esportivas com nome, descrição e endereço.
- 🥅 **Cadastro de Quadras:** cada arena pode possuir quadras com modalidade, preço por hora, capacidade e disponibilidade.
- 🔎 **Consulta de Arenas e Quadras:** clientes podem visualizar locais e quadras disponíveis.
- 📅 **Solicitação de Reserva:** clientes podem solicitar reserva informando quadra, data e horário.
- ✅ **Aceite de Reserva:** prestadores podem aceitar reservas pendentes.
- ❌ **Recusa de Reserva:** prestadores podem recusar solicitações e registrar motivo.
- 🚫 **Cancelamento de Reserva:** clientes podem cancelar solicitações conforme regras de negócio.
- 📨 **Sistema de Notificações:** envio fictício de notificações por e-mail, push ou alerta interno.
- 🧵 **Mensageria Assíncrona:** publicação de eventos de reserva no RabbitMQ.
- 📊 **Relatórios Administrativos:** visão geral de reservas, usuários, arenas e quadras.
- 📘 **Documentação Técnica:** modelagem com PlantUML, diagramas UML e README acadêmico.

---

## 🛠 Tecnologias Utilizadas

As seguintes ferramentas, frameworks e bibliotecas foram utilizados na projeção fictícia deste projeto. As versões listadas servem como referência para compatibilidade.

### 💻 Front-end

* **Framework/Biblioteca:** React 19.1.1
* **Linguagem/Superset:** TypeScript 5.x
* **Estilização:** Tailwind CSS 4.x
* **Gerenciamento de Estado:** Zustand
* **Build Tool:** Vite 7.1.2
* **Roteamento:** React Router DOM
* **Cliente HTTP:** Axios
* **Validação de Formulários:** React Hook Form + Zod
* **Testes:** Vitest e Testing Library

### 🖥️ Back-end

* **Linguagem/Runtime:** Python 3.12
* **Framework:** Flask 3.0
* **Banco de Dados:** PostgreSQL 16
* **ORM / Query Builder:** SQLAlchemy 2.x
* **Migrações:** Flask-Migrate / Alembic
* **Autenticação:** JWT com Flask-JWT-Extended
* **Validação:** Marshmallow
* **Documentação da API:** Swagger/OpenAPI
* **Testes:** Pytest

### 📱 Mobile (Opcional)

* **Framework:** Flutter 3.x
* **Linguagem:** Dart
* **Ferramentas:** Android Studio, Gradle e emulador Android
* **Comunicação:** Consumo da API REST do HubArena

### ⚙️ Infraestrutura & DevOps

* **Containerização:** Docker
* **Orquestração:** Docker Compose
* **Mensageria:** RabbitMQ 3.13
* **Cloud:** Vercel para front-end, Render para back-end, Supabase PostgreSQL e CloudAMQP
* **CI/CD:** GitHub Actions
* **Monitoramento:** Sentry, Grafana Cloud e logs estruturados
* **Testes de API:** Postman

---

## 🏗 Arquitetura

O **HubArena** foi projetado com uma arquitetura em camadas, separando as responsabilidades de apresentação, comunicação, regras de negócio, persistência de dados e mensageria. Essa organização facilita a manutenção, a evolução e a compreensão da aplicação.

A camada de apresentação é composta por uma aplicação web/mobile, responsável pela interação com clientes, prestadores e administradores. A comunicação com o back-end ocorre por meio de requisições HTTP no padrão REST, utilizando JSON como formato de troca de dados.

O back-end é estruturado em rotas, controllers, services, repositories e models. As rotas recebem as requisições HTTP, os controllers coordenam as chamadas, os services concentram as regras de negócio, os repositories acessam os dados persistidos e os models representam as entidades principais do domínio.

O banco de dados PostgreSQL armazena usuários, arenas, quadras e reservas. O RabbitMQ é utilizado como middleware de mensageria para publicar eventos relacionados às reservas, como criação, aceite, recusa ou cancelamento. Um serviço de notificação consome esses eventos para enviar avisos aos usuários.

### Padrões arquiteturais adotados

- **Arquitetura em camadas:** separação entre apresentação, controle, serviço, persistência e infraestrutura.
- **MVC adaptado:** divisão entre interface, controle da aplicação e modelos de domínio.
- **Service Layer:** centralização das regras de negócio.
- **Repository Pattern:** isolamento do acesso ao banco de dados.
- **DTO/Schema:** transporte e validação dos dados entre camadas.
- **Event-Driven Architecture:** publicação de eventos de domínio no RabbitMQ.
- **ORM:** mapeamento entre classes Python e tabelas relacionais.

### Fluxo de dados resumido

```text
Cliente / Prestador / Administrador
        ↓
Interface Web ou Mobile
        ↓ HTTP/JSON
API Back-end Flask
        ↓
Controllers
        ↓
Services
        ↓
Repositories
        ↓
PostgreSQL

ReservationService
        ↓ Evento de domínio
RabbitMQ
        ↓
Serviço de Notificação
```

### Exemplos de diagramas

Para melhor visualização e entendimento da estrutura do sistema, os diagramas principais estão organizados lado a lado.

| Diagrama de Arquitetura | Detalhe da Arquitetura |
| :---: | :---: |
| **Visão Geral C4/Macro** | **Diagrama de Componentes** |
| <img src="./docs/images/arquitetura_c4.png" alt="Diagrama de Arquitetura do HubArena" width="220px"> | <img src="./docs/images/diagrama_componentes.png" alt="Diagrama de Componentes do HubArena" width="220px"> |
| **Modelo de Dados / DER** | **Fluxo de Reserva** |
| <img src="./docs/images/modelo_dados.png" alt="Modelo de Dados do HubArena" width="220px"> | <img src="./docs/images/sequencia_reserva.png" alt="Diagrama de Sequência de Reserva" width="220px"> |
| **Implantação Docker** | **Estados da Reserva** |
| <img src="./docs/images/diagrama_implantacao.png" alt="Diagrama de Implantação do HubArena" width="220px"> | <img src="./docs/images/estados_reserva.png" alt="Diagrama de Estados da Reserva" width="220px"> |

---

## 🔧 Instalação e Execução

### Pré-requisitos
Certifique-se de que o usuário tenha o ambiente configurado.

* **Python:** versão 3.12 ou superior para o back-end Flask.
* **Node.js:** versão LTS 20.x ou superior para o front-end React.
* **Gerenciador de Pacotes:** npm ou yarn.
* **Docker:** recomendado para PostgreSQL e RabbitMQ.
* **Postman:** recomendado para testar os endpoints REST.
* **PlantUML:** recomendado para gerar os diagramas a partir dos arquivos `.puml`.
* **Git:** necessário para clonar e versionar o projeto.

---

### 🔑 Variáveis de Ambiente

Crie arquivos `.env` específicos e/ou configure as variáveis de ambiente no seu sistema para cada parte da aplicação.

#### 1 Back-end Flask

Configure estas variáveis no arquivo `/backend/.env`:

| Variável | Descrição | Exemplo |
| :--- | :--- | :--- |
| `FLASK_ENV` | Ambiente de execução da aplicação Flask. | `development` |
| `FLASK_APP` | Arquivo principal da aplicação. | `run.py` |
| `SERVER_PORT` | Porta onde o back-end será executado. | `5000` |
| `DATABASE_URL` | URL de conexão com o PostgreSQL. | `postgresql://hubarena_user:hubarena_pass@localhost:5432/hubarena_db` |
| `JWT_SECRET_KEY` | Chave secreta para assinatura de tokens JWT. | `hubarena_super_secret_key` |
| `RABBITMQ_HOST` | Host do serviço RabbitMQ. | `localhost` |
| `RABBITMQ_PORT` | Porta AMQP do RabbitMQ. | `5672` |
| `RABBITMQ_USER` | Usuário do RabbitMQ. | `guest` |
| `RABBITMQ_PASSWORD` | Senha do RabbitMQ. | `guest` |
| `RABBITMQ_QUEUE` | Fila principal de eventos de reserva. | `hubarena.reservations.events` |

Exemplo de arquivo `.env`:

```env
FLASK_ENV=development
FLASK_APP=run.py
SERVER_PORT=5000

DATABASE_URL=postgresql://hubarena_user:hubarena_pass@localhost:5432/hubarena_db

JWT_SECRET_KEY=hubarena_super_secret_key

RABBITMQ_HOST=localhost
RABBITMQ_PORT=5672
RABBITMQ_USER=guest
RABBITMQ_PASSWORD=guest
RABBITMQ_QUEUE=hubarena.reservations.events
```

#### 2 Front-end React, Vite

Crie um arquivo **`.env.local`** na raiz da pasta `/frontend` e use o prefixo `VITE_` para expor as variáveis ao bundle da aplicação.

| Variável | Descrição | Exemplo |
| :--- | :--- | :--- |
| `VITE_API_URL` | URL base da API Flask. | `http://localhost:5000/api` |
| `VITE_APP_NAME` | Nome exibido na aplicação. | `HubArena` |
| `VITE_ENABLE_NOTIFICATIONS` | Habilita comportamento visual de notificações. | `true` |

Exemplo:

```env
VITE_API_URL=http://localhost:5000/api
VITE_APP_NAME=HubArena
VITE_ENABLE_NOTIFICATIONS=true
```

---

#### 3 Exemplos de Variáveis de Ambiente na Vercel

A Vercel permite configurar variáveis no painel **Project Settings > Environment Variables**. Aqui estão exemplos fictícios utilizados no HubArena.

##### Exemplo 1 – Front-end com Vite consumindo API externa

```env
VITE_API_URL=https://hubarena-api.onrender.com/api
VITE_APP_NAME=HubArena
VITE_ENABLE_NOTIFICATIONS=true
```

##### Exemplo 2 – Aplicação com API hospedada em Render

```env
RENDER_API_URL=https://hubarena-api.onrender.com
JWT_PUBLIC_KEY=hubarena_public_key
```

##### Exemplo 3 – Integração com serviços de notificação

```env
VITE_EMAIL_SERVICE_ID=hubarena_email_service
VITE_PUSH_PUBLIC_KEY=hubarena_push_public_key
```

##### Exemplo 4 – Frontend com Vite

```env
VITE_API_URL=http://localhost:5000/api
VITE_APP_NAME=HubArena
VITE_ENABLE_NOTIFICATIONS=true
```

> **Obs:** As variáveis de ambiente em projetos **Vite** precisam começar com `VITE_` para que sejam reconhecidas pelo front-end.

Para adicionar essas variáveis:

1. Acesse a página de Environment Variables do projeto na Vercel.
2. Clique em **Add**.
3. Informe nome, valor e ambiente.
4. Salve as alterações e faça novo deploy.

Alternativamente, em ambiente local, crie o arquivo:

```text
/frontend/.env.local
```

---

### 📦 Instalação de Dependências

Clone o repositório e instale as dependências.

1. **Clone o Repositório:**

```bash
git clone https://github.com/seu-usuario/hubarena.git
cd hubarena
```

2. **Instale as Dependências do Monorepo:**

Como o projeto está dividido em front-end e back-end, as dependências devem ser instaladas separadamente.

#### Front-end React

Acesse a pasta do front-end e instale as dependências do Node.js:

```bash
cd frontend
npm install
cd ..
```

Opcionalmente, usando yarn:

```bash
cd frontend
yarn install
cd ..
```

#### Back-end Flask

O back-end utiliza Python, Flask e SQLAlchemy. Crie o ambiente virtual e instale as dependências:

```bash
cd backend
python -m venv venv
```

Ativação no Windows:

```bash
venv\Scripts\activate
```

Ativação no Linux/Mac:

```bash
source venv/bin/activate
```

Instalação:

```bash
pip install -r requirements.txt
cd ..
```

---

### 💾 Inicialização do Banco de Dados PostgreSQL

O projeto utiliza **PostgreSQL**. A forma mais simples de inicializar o banco é via Docker.

1. **Rode o container do PostgreSQL:**

```bash
docker run --name hubarena_postgres \
  -e POSTGRES_USER=hubarena_user \
  -e POSTGRES_PASSWORD=hubarena_pass \
  -e POSTGRES_DB=hubarena_db \
  -p 5432:5432 \
  -d postgres:16
```

2. **Rode o container do RabbitMQ:**

```bash
docker run --name hubarena_rabbitmq \
  -p 5672:5672 \
  -p 15672:15672 \
  -d rabbitmq:3-management
```

3. **Execute as migrações do banco:**

```bash
cd backend
flask db upgrade
cd ..
```

> [!NOTE]
> Caso o projeto seja executado com Docker Compose, os serviços de banco de dados e mensageria serão inicializados automaticamente conforme o arquivo `docker-compose.yml`.

---

### ⚡ Como Executar a Aplicação

Execute a aplicação em modo de desenvolvimento em terminais separados.

#### Terminal 1: Back-end Flask

Inicie a API Flask:

```bash
cd backend
python run.py
```

A API estará disponível em:

```text
http://localhost:5000
```

Endpoints principais de saúde:

```text
GET http://localhost:5000/health/api
GET http://localhost:5000/health/db
GET http://localhost:5000/health/rabbitmq
```

---

#### Terminal 2: Front-end React, Vite

Inicie o servidor de desenvolvimento do front-end:

```bash
cd frontend
npm run dev
```

A aplicação estará disponível em:

```text
http://localhost:5173
```

---

#### 🐳 Execução Local Completa com Docker Compose Incluindo Banco de Dados

Para uma execução local que inclui back-end, front-end, PostgreSQL e RabbitMQ, utilize Docker Compose.

Antes de tudo, certifique-se de que o **Docker Desktop** está em execução.

- **No Windows/Mac:** abra o Docker Desktop.
- **No Linux:** execute:

```bash
sudo systemctl start docker
```

---

#### 📦 Passos para build, inicialização e execução

1. Acesse a pasta raiz do projeto:

```bash
cd /caminho/do/projeto/hubarena
```

2. Suba todos os serviços:

```bash
docker-compose up --build -d
```

3. Verifique se os containers estão rodando:

```bash
docker ps
```

4. Verifique os logs do back-end:

```bash
docker logs hubarena_backend
```

5. Acesse os serviços:

```text
Front-end: http://localhost:5173
Back-end: http://localhost:5000
RabbitMQ Management: http://localhost:15672
PostgreSQL: localhost:5432
```

Credenciais fictícias do RabbitMQ:

```text
Usuário: guest
Senha: guest
```

6. Para parar os serviços:

```bash
docker-compose down
```

7. Para remover volumes e reiniciar o ambiente:

```bash
docker-compose down -v
docker-compose up --build -d
```

✅ **Em resumo:** O Docker Compose simplifica a execução local, isolando front-end, back-end, banco de dados e mensageria.

---

## 🚀 Deploy

Instruções fictícias para deploy em produção.

1. **Build do Projeto:**

Execute o build separadamente para front-end e back-end.

```bash
# Build do Front-end React/Vite
cd frontend
npm run build

# Retorna para a raiz
cd ..

# Preparação do Back-end Flask
cd backend
pip install -r requirements.txt
```

2. **Configuração do Ambiente de Produção:**

Configure as variáveis no provedor de hospedagem.

Variáveis importantes do back-end:

```env
FLASK_ENV=production
DATABASE_URL=postgresql://hubarena_admin:senha@db.supabase.co:5432/hubarena_db
JWT_SECRET_KEY=chave_producao_hubarena
RABBITMQ_HOST=cloudamqp-hubarena.com
RABBITMQ_PORT=5672
RABBITMQ_USER=hubarena_user
RABBITMQ_PASSWORD=senha_segura
```

Variáveis importantes do front-end:

```env
VITE_API_URL=https://hubarena-api.onrender.com/api
VITE_APP_NAME=HubArena
```

3. **Execução em Produção:**

Back-end Flask em Render:

```bash
gunicorn run:app
```

Front-end em Vercel:

```bash
npm run build
```

A pasta de saída será:

```text
frontend/dist
```

4. **Serviços sugeridos:**

| Camada | Serviço fictício |
| :--- | :--- |
| Front-end | Vercel |
| Back-end | Render |
| Banco de Dados | Supabase PostgreSQL |
| Mensageria | CloudAMQP |
| Monitoramento | Sentry / Grafana Cloud |

---

## 📂 Estrutura de Pastas

Descreva o propósito das pastas principais.

```text
hubarena/
├── .editorconfig                # Padronização de estilo de código.
├── .env.example                 # Exemplo de variáveis de ambiente.
├── .gitignore                   # Arquivos e pastas ignorados pelo Git.
├── README.md                    # Documentação principal do projeto.
├── LICENSE                      # Licença do projeto.
├── docker-compose.yml           # Orquestração local dos containers.
│
├── backend/                     # API Flask do HubArena.
│   ├── run.py                   # Arquivo principal para execução da API.
│   ├── requirements.txt         # Dependências Python do back-end.
│   ├── Dockerfile               # Dockerfile do back-end.
│   │
│   ├── app/                     # Pacote principal da aplicação.
│   │   ├── __init__.py          # Inicialização da aplicação Flask.
│   │   ├── config/              # Configurações da aplicação.
│   │   │   └── config.py
│   │   ├── routes/              # Rotas HTTP da API.
│   │   │   ├── user_routes.py
│   │   │   ├── arena_routes.py
│   │   │   ├── court_routes.py
│   │   │   ├── reservation_routes.py
│   │   │   └── health_routes.py
│   │   ├── controllers/         # Controllers responsáveis por coordenar requisições.
│   │   │   ├── user_controller.py
│   │   │   ├── arena_controller.py
│   │   │   ├── court_controller.py
│   │   │   └── reservation_controller.py
│   │   ├── services/            # Regras de negócio.
│   │   │   ├── user_service.py
│   │   │   ├── arena_service.py
│   │   │   ├── court_service.py
│   │   │   └── reservation_service.py
│   │   ├── repositories/        # Acesso aos dados.
│   │   │   ├── user_repository.py
│   │   │   ├── arena_repository.py
│   │   │   ├── court_repository.py
│   │   │   └── reservation_repository.py
│   │   ├── models/              # Entidades do domínio.
│   │   │   ├── user.py
│   │   │   ├── arena.py
│   │   │   ├── court.py
│   │   │   └── reservation.py
│   │   ├── messaging/           # Integração com RabbitMQ.
│   │   │   ├── rabbitmq_client.py
│   │   │   └── event_publisher.py
│   │   └── database/            # Configuração de banco de dados.
│   │       └── db.py
│   │
│   └── tests/                   # Testes do back-end.
│       ├── unit/
│       └── integration/
│
├── frontend/                    # Aplicação React.
│   ├── .env.example             # Exemplo de variáveis do front-end.
│   ├── package.json             # Dependências e scripts Node.js.
│   ├── vite.config.ts           # Configuração do Vite.
│   ├── Dockerfile               # Dockerfile do front-end.
│   ├── public/                  # Arquivos estáticos.
│   └── src/                     # Código-fonte React.
│       ├── components/          # Componentes reutilizáveis.
│       ├── pages/               # Páginas da aplicação.
│       ├── services/            # Comunicação com API.
│       ├── hooks/               # Hooks personalizados.
│       ├── styles/              # Estilos globais.
│       ├── assets/              # Imagens, ícones e recursos.
│       └── utils/               # Funções utilitárias.
│
├── docs/                        # Documentação do projeto.
│   ├── HubArena_Documentacao_de_Projeto.pdf
│   ├── images/                  # Imagens dos diagramas.
│   ├── plantuml/                # Códigos PlantUML.
│   └── postman/                 # Collections do Postman.
│
└── tests/                       # Testes end-to-end.
    └── e2e/
```

---

## 🎥 Demonstração

Use GIFs e prints para mostrar o projeto em ação.

> [!WARNING]
> Como este projeto possui finalidade acadêmica e foco em documentação, as imagens abaixo são referências fictícias. Em uma implementação real, recomenda-se substituir os placeholders por capturas reais da aplicação.

### 📱 Aplicativo Mobile

- GIF de demonstração fictício do fluxo de reserva:

| Demonstração 1 | Demonstração 2 | Demonstração 3 | Demonstração 4 |
|----------------|----------------|----------------|----------------|
| <img src="https://joaopauloaramuni.github.io/image/fundo_mobile_engsoft.jpeg" alt="Login Mobile" height="400"> | <img src="https://joaopauloaramuni.github.io/image/fundo_mobile_engsoft.jpeg" alt="Lista de Arenas" height="400"> | <img src="https://joaopauloaramuni.github.io/image/fundo_mobile_engsoft.jpeg" alt="Detalhes da Quadra" height="400"> | <img src="https://joaopauloaramuni.github.io/image/fundo_mobile_engsoft.jpeg" alt="Reserva Mobile" height="400"> |
| _Login do usuário_ | _Consulta de arenas_ | _Seleção da quadra_ | _Solicitação de reserva_ |

Para melhor visualização, as telas principais estão organizadas lado a lado.

| Tela | Captura de Tela |
| :---: | :---: |
| **Tela Inicial** | **Tela de Perfil** |
| <img src="https://joaopauloaramuni.github.io/image/aramunilogo.png" alt="Tela Inicial Mobile" width="120px" height="120px"> | <img src="https://joaopauloaramuni.github.io/image/aramunilogo.png" alt="Tela de Perfil Mobile" width="120px" height="120px"> |
| **Tela de Cadastro** | **Tela de Reservas** |
| <img src="https://joaopauloaramuni.github.io/image/aramunilogo.png" alt="Tela de Cadastro Mobile" width="120px" height="120px"> | <img src="https://joaopauloaramuni.github.io/image/aramunilogo.png" alt="Tela de Reservas Mobile" width="120px" height="120px"> |

### 🌐 Aplicação Web

Para melhor visualização, as telas principais estão organizadas lado a lado.

| Tela | Captura de Tela |
| :---: | :---: |
| **Página Inicial Home** | **Página de Login** |
| <img src="https://joaopauloaramuni.github.io/image/aramunilogo.png" alt="Home Web" width="120px" height="120px"> | <img src="https://joaopauloaramuni.github.io/image/aramunilogo.png" alt="Login Web" width="120px" height="120px"> |
| **Consulta de Arenas** | **Consulta de Quadras** |
| <img src="https://joaopauloaramuni.github.io/image/aramunilogo.png" alt="Arenas Web" width="120px" height="120px"> | <img src="https://joaopauloaramuni.github.io/image/aramunilogo.png" alt="Quadras Web" width="120px" height="120px"> |
| **Solicitação de Reserva** | **Painel do Prestador** |
| <img src="https://joaopauloaramuni.github.io/image/aramunilogo.png" alt="Reserva Web" width="120px" height="120px"> | <img src="https://joaopauloaramuni.github.io/image/aramunilogo.png" alt="Painel Prestador" width="120px" height="120px"> |

### 💻 Exemplo de Saída no Terminal para Back-end, API, CLI

Caso o projeto seja focado em serviços de back-end, API ou scripts, utilize esta seção para demonstrar a interação com o sistema.

#### 1. Demonstração da API com Postman ou cURL

Exemplo de criação de reserva:

```bash
curl -X POST 'http://localhost:5000/api/reservations' \
     -H 'Content-Type: application/json' \
     -H 'Authorization: Bearer <seu-jwt-token>' \
     -d '{
       "clientId": 2,
       "courtId": 1,
       "date": "2026-06-12",
       "startTime": "19:00",
       "endTime": "20:00"
     }'
```

**Saída Esperada:**

```json
{
  "id": 1,
  "clientId": 2,
  "courtId": 1,
  "date": "2026-06-12",
  "startTime": "19:00",
  "endTime": "20:00",
  "status": "PENDING",
  "message": "Reserva solicitada com sucesso."
}
```

#### 2. Demonstração de Execução de CLI/Script

Exemplo fictício para validar saúde do ambiente:

```bash
python scripts/check_environment.py
```

**Saída Esperada:**

```text
[INFO] Verificando ambiente HubArena...
[SUCCESS] API Flask disponível em http://localhost:5000
[SUCCESS] PostgreSQL conectado em localhost:5432
[SUCCESS] RabbitMQ conectado em localhost:5672
[SUCCESS] Fila hubarena.reservations.events disponível
[SUCCESS] Ambiente validado com sucesso.
Tempo de execução: 1.12s
```

---

## 🧪 Testes

### Testes Unitários e de Integração

Para rodar os testes do back-end:

```bash
cd backend
pytest
```

Ferramentas utilizadas:

```text
Pytest
pytest-flask
coverage.py
```

### Testes End-to-End E2E

Para rodar os testes de ponta a ponta:

```bash
cd tests/e2e
npx playwright test
```

Ferramenta utilizada:

```text
Playwright
```

### Testes do Front-end

Para rodar os testes do front-end:

```bash
cd frontend
npm run test
```

Ferramentas utilizadas:

```text
Vitest
Testing Library
```

### Testes da API com Postman

Importe a collection fictícia:

```text
docs/postman/HubArena.postman_collection.json
```

Endpoints principais:

```text
GET    /health/api
GET    /health/db
GET    /health/rabbitmq
POST   /users
GET    /users
POST   /arenas
GET    /arenas
POST   /courts
GET    /courts
POST   /reservations
GET    /reservations
PATCH  /reservations/{id}/accept
PATCH  /reservations/{id}/reject
```

---

## 🔗 Documentações utilizadas

Liste aqui links para documentação técnica, referências de bibliotecas complexas ou guias de estilo que foram cruciais para o projeto.

* 📖 **Framework Front-end:** [Documentação Oficial do React](https://react.dev/)
* 📖 **Build Tool Front-end:** [Documentação Oficial do Vite](https://vite.dev/)
* 📖 **Linguagem Front-end:** [Documentação Oficial do TypeScript](https://www.typescriptlang.org/docs/)
* 📖 **Framework Back-end:** [Documentação Oficial do Flask](https://flask.palletsprojects.com/)
* 📖 **ORM:** [Documentação Oficial do SQLAlchemy](https://www.sqlalchemy.org/)
* 📖 **Banco de Dados:** [Documentação Oficial do PostgreSQL](https://www.postgresql.org/docs/)
* 📖 **Mensageria:** [Documentação Oficial do RabbitMQ](https://www.rabbitmq.com/docs)
* 📖 **Containerização:** [Documentação de Referência do Docker](https://docs.docker.com/)
* 📖 **Modelagem UML:** [Documentação Oficial do PlantUML](https://plantuml.com/)
* 📖 **Testes de API:** [Documentação do Postman](https://learning.postman.com/docs/introduction/overview/)
* 📖 **Guia de Estilo:** [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

---

## 👥 Autores

Liste os principais contribuidores. Você pode usar links para seus perfis.

| 👤 Nome | 🖼️ Foto | :octocat: GitHub | 💼 LinkedIn | 📤 Gmail |
|---------|----------|-----------------|-------------|-----------|
| Rael Kiluanji de Jesus Cassimiro | <div align="center"><img src="https://joaopauloaramuni.github.io/image/aramunilogo.png" width="70px" height="70px"></div> | <div align="center"><a href="https://github.com/RaelK"><img src="https://joaopauloaramuni.github.io/image/github6.png" width="50px" height="50px"></a></div> | <div align="center"><a href="https://www.linkedin.com/in/rael-kiluanji"><img src="https://joaopauloaramuni.github.io/image/linkedin2.png" width="50px" height="50px"></a></div> | <div align="center"><a href="mailto:contato@hubarena.dev"><img src="https://joaopauloaramuni.github.io/image/gmail3.png" width="50px" height="50px"></a></div> |

> [!TIP]
> Em uma entrega real, substitua os links fictícios por perfis oficiais do autor.

---

## 🤝 Contribuição

Guia para contribuições ao projeto.

1. Faça um `fork` do projeto.
2. Crie uma branch para sua feature:

```bash
git checkout -b feature/minha-feature
```

3. Commit suas mudanças:

```bash
git commit -m "feat: adiciona nova funcionalidade"
```

4. Faça o push para a branch:

```bash
git push origin feature/minha-feature
```

5. Abra um Pull Request.

> [!IMPORTANT]
> Utilize mensagens de commit no padrão **Conventional Commits**. Como este projeto tem finalidade acadêmica, qualquer contribuição deve manter coerência com a documentação UML, as regras de negócio e a arquitetura projetada.

---

## 🙏 Agradecimentos

Gostaria de agradecer à disciplina **Projeto de Software** pela orientação metodológica no desenvolvimento da documentação do sistema HubArena.

Também agradeço às referências de engenharia de software, modelagem UML, arquitetura de sistemas, documentação em Markdown e ao uso do **PlantUML** como ferramenta principal para criação dos diagramas exigidos no trabalho.

Agradecimentos especiais à comunidade de desenvolvimento de software e às documentações oficiais das tecnologias utilizadas de forma fictícia no projeto, como React, Flask, PostgreSQL, RabbitMQ, Docker e PlantUML.

---

## 📄 Licença

Este projeto é distribuído sob a **Licença MIT**.

```text
MIT License

Copyright (c) 2026 HubArena

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files, to deal in the Software
without restriction, including without limitation the rights to use, copy,
modify, merge, publish, distribute, sublicense, and/or sell copies of the Software,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---
