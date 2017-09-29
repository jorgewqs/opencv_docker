# opencv_docker
This repository helps creating a docker container that runs opencv


## Docker installation ##

The installation of Docker is easy in Ubuntu 14.04 or latter. Just issue the command:

```bash
sudo apt-get install -y docker.io
```

## Installing and running the container ##

```bash
docker build -t opencv github.com/h3dema/opencv_docker
docker run -it opencv
```
