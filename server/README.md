# NLW Setup

## Class 01

### Server ambient setup

```npm init -y``` Create package.json

```npm i fastify``` Install Fastify

---
Criar a pasta src/server.ts

---
```npm i typescript -D``` Install TypeScript into devDependencies

```npx tsc --init``` Initiate TypeScript

---
tsconfig.json Change "target": "es202";

```npm i tsx -D``` Execute TypeScript files

### Prisma setup

```npm i -D prisma```

```npm i @prisma/client```

```npx prisma init --datasource-provider SQLite```

---
Criar a tabela no schema.prisma

---
```npx prisma migrate dev```
[...]create table habits

---
```npx prisma studio```

### CORS setup

```npm i @fastify/cors```
