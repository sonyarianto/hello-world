# C++

```bash
docker run -v .:/usr/src/app -w /usr/src/app -it --rm buildpack-deps:latest sh -c "g++ -o main main.cpp && ./main"
```