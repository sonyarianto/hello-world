# C++

```bash
docker run -v .:/usr/src/app -w /usr/src/app buildpack-deps:latest sh -c "g++ -o main main.cpp && ./main"
```