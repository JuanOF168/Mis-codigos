# Clasificación de tumores de mama (Breast Cancer Wisconsin)

Proyecto final de Ciencia de Datos en el Centro Universitario UAEM Texcoco
Autor: Juan Jose Ortiz Flores
Instructor: M. en C. Benito Samuel López Razo

## Contenido del proyecto

Se trabaja con el dataset público Breast Cancer Wisconsin (Diagnostic) de UCI (569 registros y 30 variables numéricas) para clasificar tumores benignos (B = 0) y malignos (M = 1)

En el notebook se prepara la información evitando fuga de datos (el escalado se ajusta solo con los datos de entrenamiento y se usa semilla fija 42), se prueban Regresión Logística como referencia, GaussianNB, SVM (lineal y RBF) y MLP, y se comparan sus resultados con validación cruzada y métricas en prueba.

## Organización de carpetas y archivos

proyecto/
  data/
    raw/
      wdbc.data
      wdbc.names
  figures/
  Proyecto.ipynb
  README.md
  requirements.txt

## Cómo ejecutarlo

1. Abrir una terminal dentro de la carpeta del proyecto.
2. Crear y activar el entorno:
   conda create -n tumores_ml python=3.11 -y
   conda activate tumores_ml
3. Instalar dependencias:
   pip install -r requirements.txt
4. Abrir JupyterLab o Jupyter Notebook, entrar a Proyecto.ipynb y ejecutar las celdas en orden.

Fuente de los datos: UCI Machine Learning Repository - Breast Cancer Wisconsin (Diagnostic), https://archive.ics.uci.edu/dataset/17/breast-cancer-wisconsin-diagnostic