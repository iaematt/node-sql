<h1>
SQL no Node.js com Sequelize
</h1>

<p>
  Níveis de abstração de base de dados, migrations, configuração do Sequelize, relacionamentos 1:N, relacionamentos N:N, queries complexas e muito mais!
</p>

## Tecnologias

- Express — Um framework de Node.js
- Sequelize — ORM de dialeto para Node.js

## Pré-requisitos

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/pt-BR/docs/install)

## Instalação e execução
1. Faça um clone desse repositório;
2. Entre na pasta `cd nodesql`;
3. Rode `yarn` para instalar as dependências;
4. Altere as credencias dentro de `.env.exemple`;
5. Renomei o arquivo `.env.exemple` para `.env`;
6. Rode `yarn sequelize db:create` para criar o banco de dados;
7. Rode `yarn sequelize db:migrate` para executar as migrations;
8. Rode `yarn dev` para iniciar o servidor.
9. Importe o arquivo `Insomnia_2019-10-16.json` desse repositório no Insomnia;

## Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---

Código escrito por Matheus Bastos, com ajuda da 💖 Rocketseat