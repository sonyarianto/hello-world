# Zig

```bash
docker run -v .:/usr/src/app -w /usr/src/app -it --rm ziglang/static-base:latest sh -c "zig build-exe main.zig && ./main"
```