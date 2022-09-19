#Backend

Observação: para rodar o backend, crie uma cópia do arquivo .env.example e o renomeie para .env, mudando o valor da variável para a localização do arquivo db.sqlite na pasta ("file:../src/database/db.sqlite")

npm i

npx prisma init --datasource-provider sqlite

npx prisma migrate dev

npm run dev

npx prisma studio
