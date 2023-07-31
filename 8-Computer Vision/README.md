# Clasificación de frescura de frutas

El ejercicio se encuentra resuelto en `computer_vision.ipynb`. Para un resumen del proceso se puede abrir `presentation.ipynb`.

## Preparación del conjunto de datos

### Manual

1. Descargar el conjunto de datos [aquí](https://share.natasquad.com/index.php/s/D2BHJSt5nY3idPd).

2. Copiar las carpetas **Test** y **Train** hacia `8-Computer Vision/data/dataset`.

### Correr celda en notebook

1. Correr celda encargadas de descargar el conjunto de datos.

## Descargar pesos preentrenados

### Manual

La solución del proyecto utiliza pesos preentrenados de **ResNet50V2** y **Xception**. Estos pesos pueden ser descargados de:

- [ResNet50V2](https://storage.googleapis.com/tensorflow/keras-applications/resnet/resnet50v2_weights_tf_dim_ordering_tf_kernels_notop.h5)
- [Xception](https://storage.googleapis.com/tensorflow/keras-applications/xception/xception_weights_tf_dim_ordering_tf_kernels_notop.h5)

Los archivos descargados deben ser copiados a `8-Computer Vision/data/resnet_base` para **ResNet50V2** y `8-Computer Vision/data/xception_base` para **Xception**. 

### Correr celda en notebook

1. Correr celda encargadas de descargar el conjunto de datos.

## Ejecución de la solución

Correr las celdas de `computer_vision.ipynb` una vez los pasos de preparación estén completados. El Notebook se creó con el objetivo de correr las celdas de manera secuencial.

El notebook se puede correr de igual manera en Colab. Se recomienda el uso de GPU para un entrenamiento en un tiempo aceptable.

## Presentación de la solución

El documento `presentation.ipynb` contiene un resumen de los procesos de la solución.  
