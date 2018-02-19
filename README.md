# asc

```
> nvidia-docker run -p 18084:8888 --name wit-cntk-jupyter -it --shm-size=1g --ulimit memlock=-1 --ulimit stack=6710886 -v /home/wit/asc:/data nvcr.io/nvidia/cntk:18.01-py3 bash
```
