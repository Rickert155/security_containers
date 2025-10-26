# hydra 

source code
- [hydra](https://github.com/vanhauser-thc/thc-hydra)

## Clone hydra

```sh
git clone https://github.com/vanhauser-thc/thc-hydra hydra/
```
## Build image
```sh
podman build -t nmap -f Containerfile
```
## Run container
```sh
podman run -it --rm --name hydra hydra:9.7
```

## Mount dir wordlist
```sh
podman run -it --rm -v $PWD/wordlist/:/root/wordlist --name hydra hydra:9.7
```
**check mount wordlist**
```sh
ls /root/wordlist/
```

## Clone package
Клонируй образ с нужной версией инструмента [package rickert155](https://github.com/users/Rickert155/packages/container/package/hydra)
