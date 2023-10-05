## Podman install Ubuntu
```
echo "deb https://download.opensuse.org/repositories/devel:/kubic:/libcontainers:/stable/xUbuntu_20.04/ /" | sudo tee /etc/apt/sources.list.d/devel:kubic:libcontainers:stable.list

sudo curl -L "https://download.opensuse.org/repositories/devel:/kubic:/libcontainers:/stable/xUbuntu_20.04/Release.key" | sudo apt-key add -

sudo apt update
sudo apt install -y podman
```
## compose
```
sudo apt install -y python3-pip

pip3 install podman-compose

podman-compose --version
```

