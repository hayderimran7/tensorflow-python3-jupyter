Tensorflow Python3 Jupyter
==========================

Docker container with python 3 version of tensorflow accompanied by jupyter

Usage
-----

```bash
$ docker run -d -p 8888:8888 --name tflow \
    -v [path-to-notebooks]:/notebooks \
    -it erroneousboat/tensorflow-python3-jupyter
```
