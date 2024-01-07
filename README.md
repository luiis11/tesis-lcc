# Tesis - Licenciatura en Ciencias de Computación (U.N.S.L)

## Implementación de modelos con Web APP 

Esta aplicación utiliza los modelos de clasificación entrenados durante el trabajo de investigación de la Tesis, con el fin de asignar grados de personalidad a un texto dado. Utiliza algoritmos de procesamiento de lenguaje natural y aprendizaje automático para clasificar el texto en diferentes categorías de personalidad, proporcionando porcentajes para cada una.

#### Página Inicial
Aqui se debe ingresar un texto de al menos 100 palabras para predecir

![App Capture 1](https://github.com/luimont/tesis-lcc/blob/main/Screenshots/capture_1.webp)

#### Resultados 
Aqui se visualizan los resultados de predicción obtenidos a partir del texto ingresado

![App Capture 2](https://github.com/luimont/tesis-lcc/blob/main/Screenshots/capture_2.webp)


### Tecnologías Utilizadas

- Python
- Flask
- Docker
- HTML, CSS, JS
- Bibliotecas ScikitLearn de Clasificadores (DTC, SVM, MNB, LR)
- Bibliotecas ScikitLearn de procesamiento de lenguaje natural (CountVectorizer, TfIdfVectorizer)

### Requisitos

- Python 3.x
- Todas las dependencias específicas (bibliotecas Python, etc.)

## Notebooks Utilizadas para los modelos

Se listan las notebooks utilizadas para los tipos de clasificacion
- Clasificación Binaria
- Clasificación MultiClase
- Clasificación Multietiqueta

![Modelos de Clasificación](https://github.com/luimont/tesis-lcc/blob/main/Screenshots/classificactions_class.png)

## Resultados Finales

Se adjunta el informe de resultados final que consta de una tabla comparativa de todos los tipos de clasificación (binaria, multiclase, multietiqueta) junto con el resultado obtenido de cada clasificador y cada modelo de representación (booleana, tf, tfidf)

[All_results.pdf](https://github.com/luimont/tesis-lcc/blob/main/Results/all_results.pdf)
