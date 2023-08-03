# C

```bash
docker run -v .:/usr/src/app -w /usr/src/app gcc:latest sh -c "gcc -o main main.c && ./main"
```