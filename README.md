# Evaluación Estética de Fotografías: Modelos Basados en Aprendizaje Profundo y de Atención

En este repositorio se plantea una solución al problema de la evaluación estética de fotografías. Este problema consiste en clasificar si una imagen dada presenta una buena o mala calidad estética. Se ha trabajado con la base de datos de imágenes AVA:

http://refbase.cvc.uab.es/files/MMP2012a.pdf

La solución planteada en este repositorio consiste en el uso de redes neuronales, en concreto se utilizan las redes neuronales recurrentes bidireccionales con unidades LSTM y los mecanismos de atención.

## Contenido del repositorio

En este repositorio se han incluido los siguientes archivos:

*   [Modelos](./Modelos): en esta carpeta se encuentran los 3 modelos basados en mecanismos de atención y redes LSTM ya entrenados listo para utilizar.

*   [Preprocesamiento_de_imagenes.ipynb](./Preprocesamiento_de_imágenes.ipynb): este cuaderno Jupyter se encarga de preprocesar las imágenes.

*   [Modelos_basados_en_aprendizaje_profundo_y_de_atencion.ipynb](./Modelos_basados_en_aprendizaje_profundo_y_de_atencion.ipynb): en este cuaderno Jupyter se encuentra el código necesario para implementar los 3 modelos basados en mecanismos de atención y redes LSTM. Para ejecutar este cuaderno es necesario disponer de las imágenes ya preprocesadas. Para ello se pueden utilizar los archivos `.zip` que se encuentran a continuación, y contienen las 255.000 imágenes de AVA ya preprocesadas:

    *   [datasetAVA_1.zip](https://drive.google.com/file/d/1VZSch0lP9ymPYvQieioPDBYCOZvXBX7d/view?usp=sharing)

    *   [datasetAVA_2.zip](https://drive.google.com/file/d/1ShHjdMeoGcTlmKU0R7PjksrBb-462JJ-/view?usp=sharing)

    *   [datasetAVA_3.zip](https://drive.google.com/file/d/1hwzmXGN-WTn3aLaIuvnSoVfHEOO1BbEH/view?usp=sharing)

    *   [datasetAVA_4.zip](https://drive.google.com/file/d/1DjWnkGYpKQyT9AsBpGKBuLlfGDzFFf1c/view?usp=sharing)

    *   [datasetAVA_5.zip](https://drive.google.com/file/d/10D-nivOp-FxKxVjEJx1d2nykiYmj7tjP/view?usp=sharing)

    También se incluye un `.csv` ([dataset.csv](./dataset.csv)) que contiene el nombre de cada imagen preprocesada dentro de cada carpeta, junto con el valor de la variable clase.

