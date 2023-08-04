# hello-world

Just a simple hello world program on different languages and just use Docker to run it. Nothing else.

## Languages

- [C](c/README.md)
- [C++](c++/README.md)
- [Go](go/README.md)
- [JavaScript](javascript/README.md)
- [PHP](php/README.md)
- [Rust](rust/README.md)

## Quick Start

Go to project directory folder and run below commands for each particular language.

### C

```bash
docker run -v ./c:/usr/src/app -w /usr/src/app -it --rm gcc:latest sh -c "gcc -o main main.c && ./main"
```

### C++

```bash
docker run -v ./c++:/usr/src/app -w /usr/src/app -it --rm buildpack-deps:latest sh -c "g++ -o main main.cpp && ./main"
```

### Go

```bash
docker run -v ./go:/go/src/app -w /go/src/app golang:latest go run main.go
```

### JavaScript

```bash
docker run -v ./javascript:/usr/src/app -w /usr/src/app node:latest node main.js
```

### PHP (CLI)

```bash
docker run -v ./php:/usr/src/app -w /usr/src/app php:latest php main.php
```

### Rust

```bash
docker run -v ./rust:/usr/src/app -w /usr/src/app -it --rm rust:latest sh -c "rustc main.rs && ./main"
```

### Zig
    
```bash
docker run -v ./zig:/usr/src/app -w /usr/src/app -it --rm buddyspencer/ziglang:latest sh -c "zig build-exe main.zig && ./main"
```

## License

MIT

Maintained by Sony Arianto Kurniawan <<sony@sony-ak.com>> and contributors.
