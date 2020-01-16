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
