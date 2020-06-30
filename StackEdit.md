# Installation Memphyno desktop

## Docker

### Install docker
```bash
sudo apt install docker.io
```

### Typing sudo
In order to avoid typing sudo every single time you run a docker command: [https://docs.docker.com/engine/install/linux-postinstall/](https://docs.docker.com/engine/install/linux-postinstall/)
```bash
sudo groupadd docker
sudo usermod -aG docker $USER
```
Close and reopen user session, then check the groups you belong to:
```bash 
groups #-> should return docker
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTc4MTc5NjM3MiwtMzMyNDU1MzYzXX0=
-->