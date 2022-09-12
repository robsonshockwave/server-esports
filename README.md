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

`"dev": "tsnd src/server.ts"`

-> delete `"type": "module",`

in tsconfig.json change
`"module": "ES2020",` for `"module": "CommonJS",`
