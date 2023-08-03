# PHP

## CLI

```bash
docker run -v .:/usr/src/app -w /usr/src/app php:latest php main.php
```

## Web

```bash
docker run -v .:/var/www/html -p 3000:80 php:latest php -S 0.0.0.0:80 -t /var/www/html
```