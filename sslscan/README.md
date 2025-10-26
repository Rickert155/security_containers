# sslscan 

source code
- [sslscan](https://github.com/rbsec/sslscan)

## Clone nmap

```sh
git clone https://github.com/rbsec/sslscan sslscan/
```
## Build image
```sh
podman build -t sslscan -f Containerfile
```
## Run container
```sh
podman run -it --rm --name sslscan sslscan:latest
```

## Clone package
Клонируй образ с нужной версией инструмента [package rickert155](https://github.com/users/Rickert155/packages/container/package/sslscan)
