# Dockerizar una aplicación en python

## Instruciones de ejecución:

1. Hacer pull de la imagen

Link a DockerHub: <a href="https://hub.docker.com/r/andreanathaliar/python-docker" target="_blank">python-docker</a>

Comando en terminal:

```
docker pull andreanathaliar/python-docker
```


2. Levantar el contenedor localmente

```
docker run -d -p 8910:8910 andreanathaliar/python-docker
```

