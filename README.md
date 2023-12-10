# pagamento-condominio

Linguagens/Frameworks:

Linguagem: TypeScript/JavaScript

Framework: express.js, nodemailer, knex, sqlite3, nodemon, node_modules, cors, socket.io,

Método de Rodagem:

Você pode usar o comando npm run dev para rodar o TypeScript diretamente: npm ts-node-dev server.ts

Use o comando npm run knex:migrate para criar a base de dados

Use o camando npm start para rodar o index.js 

Use qualquer navegador para rodar a página html index.html: http://localhost:3000/

Use insomnia ou Postman para rodar as rotas do Router.ts:

a) Folder: Apartamento 

Método Post: Criar
  url: _base_url/Apartamento
  Json: {"Cod_Apartamento":"digite um código de apartamento",
  "Preco_Mensalidade":"Digite um preco",
  "Descricao":"Digite uma descrição"}

  Metodo Get: Buscar
  url: _base_url/Apartamento

b) Folder: Morador

Método Post: Criar

url: _base_url/Morador

json: {"nome":"Digite nome",
        "email":"digite um email "}

  Método Get: Buscar
  url: _base_url/Morador


  C) Folder: Aluguer

  Método Post: Criar

  url: _base_url/Aluguer

  json: {"Cod_Apartamento": "Digite código de um apartamento",
  "nome":"digite nome do morador",
  "Data_Final":"Digite a Data_Final"}

  Método Get: Buscar
  url: _base_url/Aluguer

  d) Folde: Pagamento

  Método Post: Criar
  url: _base_url/Pagamento

  json: {"nome":"Digite o nome do morador",
  "Cod_Apartamento":"Digite o código do Apartamento"}

  Metodo Get: Buscar 
  url: _base_url/Pagamento

  


