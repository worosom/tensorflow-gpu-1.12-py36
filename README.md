# Docker TensorFlow with python 3.6 and GPU support

[![Docker Cloud Automated build](https://img.shields.io/docker/cloud/automated/morosow/tensorflow-gpu-1.12-py36.svg)](https://hub.docker.com/r/morosow/tensorflow-gpu-1.12-py36/)


To pull

    docker pull morosow/tensorflow-gpu-1.12-py36
    
 
To test (with `nvidia-docker` installed)

    nvidia-docker run --rm -v $PWD/test.py:/run.py morosow/tensorflow-gpu-1.12-py36 python /run.py
