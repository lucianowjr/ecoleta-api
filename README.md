<h1 align="center">
    <img alt="Ecoleta" title="Ecoleta" src="public/logo.svg">
    <br/>
    <img alt="Ecoleta" title="Ecoleta" width="250px" src="public/ecoleta.png">
</h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/lucianowjr/ecoleta-api">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/lucianowjr/ecoleta-api">
  
  <a href="https://github.com/raphabarreto/ecoleta/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/lucianowjr/ecoleta-api">
  </a>

  <a href="https://github.com/raphabarreto/ecoleta/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/lucianowjr/ecoleta-api">
  </a>

  <a href="https://github.com/raphabarreto/ecoleta/blob/master/LICENSE.md">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
  <a>
</p>

# Índice
- [Sobre](#-sobre)
- [Tecnologias utilizadas](#-tecnologias-utilizadas)
- [Conhecimentos adquiridos](#-conhecimentos-adquiridos)
- [Como utilizar o projeto](#-como-utilizar-o-projeto)

# 📄 Sobre

O **Ecoleta** é um marketplace de coleta de resíduos recicláveis, onde é possível o cadastro de pontos de coleta e consulta da localização desses pontos. <br>
Este projeto foi desenvolvido durante a **Next Level Week** da **Rocketseat**.

---

# 🖥 Tecnologias utilizadas
- [Node](https://nodejs.org/) / [Express](https://expressjs.com/)
- [Typescript](https://www.typescriptlang.org/)
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Aprender/JavaScript)
- [SQLite](https://www.sqlite.org/)


---

# ✍ Conhecimentos adquiridos
- Utilização do Framework Node.js e Express
- Utilização do Typescript
- Integração com a biblioteca Axios
- Integração com a biblioteca Knex (SQL query builder)  
- Configuração e utilização de rotas

---

# 📦 Como utilizar o projeto
```bash

    # Clonar o repositório
    $ git clone https://github.com/lucianowjr/ecoleta-api

    # Entrar no diretório do projeto
    $ cd ecoleta-api

    # Instalar as dependências        
    $ yarn install 
    
    # Execute os seguintes comandos para congfigurar o banco de dados
    $ yarn knex:migrate
    $ yarn knex:seed

    # Iniciar o projeto
    $ yarn run dev

    # Observações:
    - Não esqueça de mudar a baseURL no arquivo api.ts das pastas web e mobile para o IP da sua máquina
```
---

Desenvolvido por [Luciano Oliveira](https://www.linkedin.com/in/lucianowjr/)
