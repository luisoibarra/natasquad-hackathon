# README

Repositorio creado para la participación en **NataSquad AI Hackathon**.

## Problemas

El problema de participación es el problema **[8 Computer Vision](/8-Computer%20Vision/README.md)**.

Además de este problema, se incursionó en darle solución parcial o total a otros problemas de la competencia.

## Cuerpo del issue de participación

```plaintext
Título:  Luis Ibarra Problema 8 Computer Vision.

Cuerpo:

Autor: Luis Ernesto Ibarra Vázquez

Correo: luise98cu@gmail.com

Número de teléfono: +53 58420636

Repositorio de solución: https://github.com/luisoibarra/natasquad-hackathon
```

## Ambiente de trabajo

Para trabajar se utiliza Python 3.8.10 sobre un contenedor de Docker con las dependencias instaladas. Se sugiere utilizar el mismo método en caso de desear correr los programas.

### Colab

Algunos notebook fueron hechos para que se pudieran ejecutar en Colab. Ejemplo de esto es el notebook del ejercicio 8.

### Pip

Se creó un `requirements.txt` en correspondencia con las instrucciones de la competencia.

### Docker

#### Construir imagen de docker

`docker build -t datascience:1.1 .\docker`

Esta imagen contiene la última versión de Tensorflow (2.13) con soporte GPU y puede abrir directamente en un Jupyter Notebook.

Paquetes instalados en la imagen:

- Tensorflow
- Scikit learn
- Auto scikit learn
- Pandas
- Seaborn

#### Correr contenedor

1. Ejecutar el comando en la terminal:
    - Windows: `docker run -it --rm -v ${PWD}:/tf/notebooks --gpus all -p 8888:8888 datascience:1.1`
    - Linux: `docker run -it --rm -v $(pwd):/tf/notebooks --gpus all -p 8888:8888 datascience:1.1`
2. Abrir un navegador con el link proporcionado en los logs de la terminal.

#### Correr como devcontainer en VSCode

El repositorio soporta el trabajo desde un Devcontainer de VSCode. Para esto:

1. Instalar extensiones para trabajar con Devcontainers
2. Abrir el devcontainer en el repositorio
