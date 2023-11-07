# Projeto de API simples com Node.js

Requisitos:
- NodeJS (https://nodejs.org/)

Clone o repositório e entre no diretório:
```bash
cd node-do-zero
```

Utilize a versão 18.16.0 do Node.js com o comando:

```bash
nvm use 18.16.0
```
Agora, instale as dependências:

```bash
npm install
```
Com as dependências instaladas, crie um arquivo .env.

Agora, é necessário utilizar o PostgreSQL. Você pode utilizar o site neon.tech para criar um banco de dados. Após a criação do banco de dados, você precisará das seguintes chaves: PGHOST, PGDATABASE, PGUSER, PGPASSWORD e ENDPOINT_ID. Elas podem ser facilmente obtidas no painel Dashboard, na seção Connect Details, copie-as e cole no arquivo .env.

Para criar as tabelas no BD, use o script:

```bash
node create_tables.js
```

Após ter feito isso, é recomendável que use a extensão do VSCode "REST CLIENT".

Pronto! Rode o projeto com o comando:

```bash
npm run dev
```

Vá para o arquivo rotas.http e divirta-se!
