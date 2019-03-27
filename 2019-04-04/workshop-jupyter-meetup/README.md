In order to run locally in docker:

```
docker build -t jupyter-image .
docker run -it -p 8888:8888 jupyter-image
```