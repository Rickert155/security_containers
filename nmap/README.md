# nmap

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
podman run -it --rm --name nmap nmap
```
