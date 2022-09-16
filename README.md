# notations

npm init -y
npm i express

`"type": "module",`

npm i typescript - D

`"build": "tsc"`

npx tsc --init

in tsconfig.json add

`"module": "ES2020",`
`"rootDir": "./src",`
`"moduleResolution": "node",`
`"outDir": "./build",`

npm i @types/express -D

npm i ts-node-dev -D

`"dev": "tsnd --exit-child src/server.ts"`

-> delete `"type": "module",`

in tsconfig.json change
`"module": "ES2020",` for `"module": "CommonJS",`

npm i prisma -D

npx prisma init -h

npx prisma init --datasource-provider SQLite

after created table in schema.prisma
npx prisma migrate dev

npx prisma studio

whenever create a table in prism run
npx prisma migrate dev

npm i @prisma/client

after modifying the schema and having installed the lib from above
npx prisma generate

npm i cors

npm i @types/cors

---

# Back-end

## Entidades

### Game

id
title
bannerUrl

### Ad

id
gameId
name
yearsPlaying
discord
weekDays
hourStart
hourEnd
useVoiceChannel
createdAt

## Casos de uso

- Listagem de games com contagem de anúncios
- Criação de novo anúncio
- Listagem de anúncios por game
- Buscar discord pelo ID do anúncio
