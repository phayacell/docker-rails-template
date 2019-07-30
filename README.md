# README

```bash
docker-compose run --rm web rails new . --force --database=mysql --skip-bundle
```

```bash
docker-compose build
```

```bash
vim config/database.yml
```

```bash
docker-compose up -d; docker-compose run --rm web rails db:create; docker-compose down
```

```bash
docker-compose up; docker-compose down
```
