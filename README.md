# hello-world

Just a simple hello world program on different languages and just use Docker to run it. Nothing else.

## Languages

- [Go](go/README.md)
- [PHP](php/README.md)
- [Rust](rust/README.md)

## Quick Start

Go

```bash
docker run -v ./go:/go/src/app -w /go/src/app golang:latest go run main.go
```

PHP

```bash
docker run -v ./php:/usr/src/app -w /usr/src/app php:latest php main.php
```

Rust

```bash
docker run -v ./rust:/usr/src/app -w /usr/src/app -it rust:latest sh -c "rustc main.rs && ./main"
```
