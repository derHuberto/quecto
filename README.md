# quecto

## Build the Yocto image

```bash
./scripts/kas-container build kas/qemuarm64.yml
```

## Build the QEMU container image

```bash
podman build -t qemu-gremlin:local containers/qemu
```

```bash
podman run --rm qemu-gremlin:local --version
```

## Run the image

```bash
./scripts/gremlin
```