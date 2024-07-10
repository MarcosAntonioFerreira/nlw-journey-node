npm init -y -> criar o package.json
npm i typescript @types/node -D  ->instalando TypeScript e dependencias
npx tsc --init -> arquivo de configuracao do type
npm i tsx -D -> forma de converter ts em js.
npx tsx watch src/server.ts - reinicia conforme cada alteracao
npm i fastify -> framework - manuntencao
npm i prisma -D -> banco de dados
npx prisma init --datasource-provider SQLite - banco de dados sqlite - salva em arquivo fisico

npx prisma migrate dev - executando código para banco de dados, cria tabela

"[prisma]":{
        "editor.formatOnSave": true
    }, dentro do settings.json garante 