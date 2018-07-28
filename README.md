## Docker setup

After you've forked, cloned and `cd`'ed into this lecture, run the following to spin up a Docker container:
```bash
docker run --name 1.01-lesson-python-intro -p 8888:8888 -v "$PWD":/home/jovyan/ jupyter/scipy-notebook
```
