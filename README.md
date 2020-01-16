# adonisJs-MySQL-docker-

docker compose base file to create an adonis + mysql project

Este ficheiro docker-compose usa as vars do adonisjs `.env`

**Create `.env` file**

**Alterar host, db_connection no ficheiro `.env` ,
Na parte db_allow_empty_password colocar para `yes`**

NOTA: colocando a variavel em "yes" não é recommendado a não ser que se saiba o que se esta fazendo :stuck_out_tongue_winking_eye:

```
HOST=0.0.0.0

DB_HOST=adonis-mysql
DB_CONNECTION=mysql
DB_ALLOW_EMPTY_PASSWORD=yes
```

## Iniciar o ambiente de desenvolvimento :

```
docker-compose up -d
```

## Entrar no container :

```
docker exec -it appname /bin/bash
```

## V2

# Adonis fullstack application

This is the fullstack boilerplate for AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Session
3. Authentication
4. Web security middleware
5. CORS
6. Edge template engine
7. Lucid ORM
8. Migrations and seeds

## Setup

Use the adonis command to install the blueprint

```bash
adonis new yardstick
```

or manually clone the repo and then run `npm install`.

### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```

## V2

# Adonis fullstack application

This is the fullstack boilerplate for AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Session
3. Authentication
4. Web security middleware
5. CORS
6. Edge template engine
7. Lucid ORM
8. Migrations and seeds

## Setup

Use the adonis command to install the blueprint

```bash
adonis new yardstick
```

or manually clone the repo and then run `npm install`.

### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```
