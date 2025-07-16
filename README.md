# Docker Todo List

Este repositório apresenta uma aplicação full-stack do tipo "to-do list", dividida em front-end, back-end e testes. O objetivo principal deste projeto foi construir e orquestrar contêineres Docker de forma eficiente, simulando um ambiente de produção real.

## 📁 Estrutura do Projeto

```text
docker/
├── docker-commands/       # Comandos CLI do Docker (desenvolvidos por mim)
├── todo-app/
│   ├── back-end/          # Base fornecida pela Trybe
│   ├── front-end/         # Base fornecida pela Trybe
│   └── tests/             # Base fornecida pela Trybe
└── docker-compose.yml     # Criado por mim para orquestração
```

## ⚙ Tecnologias Utilizadas

* Docker
* Docker Compose
* Node.js (v16)
* React
* Puppeteer

## ✅ O que foi desenvolvido por mim

* Comandos Docker específicos para criação, execução, inspeção e remoção de contêineres
* `Dockerfile` customizado para cada serviço da aplicação (back-end, front-end e testes)
* Arquivo `docker-compose.yml` para orquestração dos serviços
* Execução de testes locais em ambiente isolado via Docker

## 🔗 Componentes fornecidos pela Trybe

* Código-fonte das aplicações localizadas em `./todo-app`
* Estrutura inicial do repositório
* Documentação dos requisitos

## 🧪 Como executar o projeto

> Pré-requisitos: Docker e Docker Compose instalados.

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/project-to-do-list.git
cd project-to-do-list/docker
```

2. Suba os serviços:

```bash
docker-compose up -d
```

3. Acesse o front-end:

[http://localhost:3000](http://localhost:3000)

4. Para rodar os testes:

```bash
docker-compose run todotests
```

## 📝 Observações

* O código das aplicações (front-end, back-end e testes) foi disponibilizado previamente pela Trybe.
* Toda a infraestrutura Docker e automação de orquestração foi desenvolvida por mim.

## 📚 Referências

* [https://docs.docker.com/](https://docs.docker.com/)
* [https://docs.docker.com/compose/](https://docs.docker.com/compose/)

```
