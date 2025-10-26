# hydra 

source code
- [hydra](https://github.com/vanhauser-thc/thc-hydra)

## Clone nmap

```sh
git clone https://github.com/vanhauser-thc/thc-hydra hydra/
```
## Build image
```sh
podman build -t nmap -f Containerfile
```
## Run container
```sh
podman run -it --rm --name nmap hydra:
```

## Clone package
Клонируй образ с нужной версией инструмента [package rickert155](https://github.com/users/Rickert155/packages/container/package/hydra)
