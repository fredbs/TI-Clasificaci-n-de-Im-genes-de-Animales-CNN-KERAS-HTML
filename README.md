# TI: Clasificación de Imágenes de Animales CNN-KERAS-HTML

**Autor:** Brito, Fred

**Resumen:**  En este proyecto trabajo de investigación se derrollara un clasificador de Imagenes de animales utilizando Redes Neuronales Convulocionales (o CNN por sus siglas en inglés:Convolutional Neural Network). Se detallará brevemente e

**Objetivo:** El objetivo de este trabajo es perfilar el uso de Clasificadores de Imagen usando Redes Neuronales Convolucionales.


**Descripción de Datos:** Set de imagenes de animales, contiene alrededor de 28K imágenes de animales de formato .jpg, .jpeg y .png. Las mismas son calidad media y de tres canales (rgb). Pertenecen a 10 categorías: 

0. 'araña'
1. 'ardilla'
2. 'caballo'
3. 'elefante'
4. 'gallina'
5. 'gato'
6. 'mariposa'
7. 'oveja'
8. 'perro'
9. 'vaca'

El directorio principal está dividido en carpetas, una para cada categoría. El recuento de imágenes para cada categoría varía de 2K a 5K unidades. Ya que el conjunto de imagenes se encuentra en un directorio principal, el mismo No se encuentra dividido en train y test.

Todas las imágenes se han recopilado de "imágenes de Google" y han sido revisadas por humanos. Hay algunos datos erróneos para simular condiciones reales (por ejemplo, imágenes tomadas por los usuarios de su aplicación).


Los mismos serán importados desde kaggle:
> https://www.kaggle.com/alessiocorrado99/animals10


Se puede usar la API command de kaggle:
> `kaggle datasets download -d alessiocorrado99/animals10`

**Tabla de Resumen:**

| Etiqueta | Tipo de Dato | Descripción |
| :--- | :--- | :--- |
| imagen | Imagen (.jpg .jpeg .png)   | Imagen de animal | 
| etiqueta  | Texto (string) | Etiqueta de clase de imagen|
