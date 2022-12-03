- Swagger: Assim como na API disponibilizada na aula, você pode acessar a documentação que criamos com o Swagger, basta executar a API e acessar a rota `a/docs`

- Beekeeper: Assim como nas aulas, recomendamos o uso do Beekeeper para visualização dos dados do banco de dados.

- Prisma Studio: Caso prefira outra forma de visualizar os dados do banco de dados, basta acessar a pasta da sua API pelo terminal e executar o comando `npx prisma studio`. Dessa forma, você vai conseguir ver as tabelas e os registros na url `http://localhost:5555/`

- Insomnia: Caso queira interagir com a API de uma maneira bem direta e fácil, você pode utilizar um API Rest Client como o Insomnia. Basta [executar o download dele](https://insomnia.rest/download) e importar [as configurações que disponibilizamos aqui](https://github.com/rocketseat-education/ignite-rn-2022-challenge-marketspace-api/blob/main/insomniaWorkspace.json). Dessa forma, você terá acesso a todas as rotas e poderá fazer as requisições diretamente por ele.

## Redefinir do banco de dados

Caso tenha tido problemas com o banco de dados e queira recomeçar, você pode redefini-lo executando o seguinte comando no terminal da API:

```bash
npx prisma migrate reset
```

A CLI irá retornar a seguinte mensagem: `Are you sure you want to reset your database? All data will be lost. › (y/N)`. Digite `y` e aperte Enter para confirmar.