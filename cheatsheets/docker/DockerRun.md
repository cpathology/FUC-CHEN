### Build docker image
* Build from Dockerfile
```
$ docker build -t fuc:chen .
```
* Or pull from Docker Hub
```
$ docker pull pingjunchen/fuc:chen
$ docker tag pingjunchen/fuc:chen fuc:chen
```
### Run docker container
* Start container w/o code/data mapping
```
$ docker run -it --rm --user $(id -u):$(id -g) \
  --shm-size=224G --gpus '"device=0,1,2,3"' --cpuset-cpus=0-39 \
  --name fuc_chen fuc:chen
```
* Start container w/ code/data mapping
```
$ docker run -it --rm --user $(id -u):$(id -g) \
  -v ${CODE_ROOT}:/App/${APP_NAME} \
  -v ${DATA_ROOT}:/Data \
  --shm-size=224G --gpus '"device=0,1,2,3"' --cpuset-cpus=0-39 \
  --name fuc_chen fuc:chen
```