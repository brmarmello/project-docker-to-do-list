<h1 align="center">Project Docker To Do List</h1>

<p align="center">✔️ Concluded - 100%</p>

## 💻 Instalando o projeto

Clone o repositório:

```
git clone git@github.com:lramos33/project-docker-to-do-list.git
```

Acesse a pasta do repositório

```
cd project-docker-to-do-list
```

## 🚀 Habilidades

- Usar comandos dockers no CLI - Interface de linha de comando;
- Criar um container Docker para uma aplicação de front-end;
- Criar um container Docker para uma aplicação de back-end;
- Criar um container Docker para uma aplicação de testes;
- Orquestrar os três containers utilizando o Docker compose.

## 🔧 Desenvolvimento

Nesse projeto foi "containerizado" as aplicações de frontend, backend e testes e criado uma conexão entre elas para orquestrar seu funcionamento.

## 📝 Requisitos do projeto

#### 1. Crie um novo container de modo interativo sem roda-lo nomeando-o como `01container` e utilizando a imagem `alpine` usando a versão `3.12`

#### 2. Inicie o container `01container`

#### 3. Liste os containers filtrando pelo nome `01container`

#### 4. Execute o comando `cat /etc/os-release` no container `01container` sem se acoplar a ele

#### 5. Remova o container `01container` que está em andamento.

#### 6. Faça o download da imagem `nginx` com a versão `1.21.3-alpine` sem criar ou rodar um container.

#### 7. Rode um novo container com a imagem  `nginx` com a versão `1.21.3-alpine` em segundo plano nomeando-o como `02images` e mapeando sua porta padrão de acesso para porta `3000` do sistema hospedeiro.

#### 8. Pare o container `02images` que está em andamento.

#### 9. Gere uma build a partir do Dockerfile do `back-end` do `todo-app` nomeando a imagem para `todobackend`.

#### 10. Gere uma build a partir do Dockerfile do `front-end` do `todo-app` nomeando a imagem para `todofrontend`.

#### 11.Gere uma build a partir do Dockerfile dos `testes` do `todo-app` nomeando a imagem para `todotests`.

## 🎁 Requisitos bônus

#### 12. Suba uma orquestração em segundo plano com o docker-compose de forma que `backend`, `frontend` e `tests` consigam se comunicar.

##

<div align="center">
  <img src="https://shields.io/github/repo-size/lramos33/project-docker-to-do-list">
  <img src="https://shields.io/github/languages/top/lramos33/project-docker-to-do-list">
  <img src="https://shields.io/github/last-commit/lramos33/project-docker-to-do-list">
</div>
