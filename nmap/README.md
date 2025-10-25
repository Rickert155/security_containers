# nmap

source code
- [nmap](https://github.com/nmap/nmap)

## Clone nmap

```sh
git clone https://github.com/nmap/nmap nmap/
```
## Build image
```sh
podman build -t nmap -f Containerfile
```
## Run container
```sh
podman run -it --rm --name nmap --privileged nmap:7.98svn
```

## Clone package
Клонируй образ с нужной версией инструмента [package rickert155](https://github.com/users/Rickert155/packages/container/package/nmap)
