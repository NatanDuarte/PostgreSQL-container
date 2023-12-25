# PostgreSQL Container

easy install postgresql for testing and studying

- first create a `.env` file

```shell
POSTGRES_PASSWORD=YOUR_CREDENTIAL_HERE
POSTGRES_USER=YOUR_CREDENTIAL_HERE
POSTGRES_DB=YOUR_CREDENTIAL_HERE
```

then:

```shell
docker compose up -d --build
```

it should be running at port 15432
