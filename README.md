# Datasets — Docencia UPC

Datasets utilizados en talleres y cursos de Data Science, Machine Learning e IA, dictados como 
asistente de aprendizaje a distancia en la Universidad Peruana de Ciencias Aplicadas (UPC).

Se consumen directamente desde notebooks de Google Colab vía raw URL — este
repo no tiene otro propósito que ese.

## Estructura

​upc-datasets-docencia/

├── ml-no-supervisado/

├── ml-otros-datasets/

├── ml-supervisado-clasificacion/

├── ml-supervisado-regresion/

└── pics-for-ml/

## Índice de datasets

| Archivo | Carpeta | Curso / módulo | Descripción breve | Fuente |
|---|---|---|---|---|
| `Car Features and MSR Price.csv` | `ml-supervisado-regresion/` | Modelos de aprendizaje supervisado por regresión | Características de autos para predicción de su precio de venta (práctica de regresión) | https://www.kaggle.com/datasets/CooperUnion/cardataset |
| `winequality.csv` | `ml-supervisado-regresion/` | Modelos de aprendizaje supervisado por regresión | Características de vinos para predicción de su calidad (práctica de regresión) | https://raw.githubusercontent.com/henrypaulett/upc-datasets-docencia/refs/heads/main/ml-supervisado-regresion/winequality.csv |
| `diabetes_dataset00.csv` | `supervisado-clasificacion/` | Modelos de aprendizaje supervisado por clasificación | Pacientes con diversos diagnósticos asociados a diabetes para práctica de clasificación | https://www.kaggle.com/datasets/ankitbatra1210/diabetes-dataset/data |
| `student_performance_data.csv` | `supervisado-clasificacion/` | Modelos de aprendizaje supervisado por clasificación | Información asociada a alumnos de educación secundaria para predicción de calificaciones (práctica de clasificación) | https://www.kaggle.com/datasets/ankitbatra1210/diabetes-dataset/data |
| `E-Comerce data 1.csv` | `ml-no-supervisado/` | Modelos de aprendizaje no supervisado | Primera parte de dataset de información de facturación en una tienda on-line de venta minorista | https://www.kaggle.com/code/marcinrutecki/clustering-methods-comprehensive-study/notebook |
| `E-Comerce data 2.csv` | `ml-no-supervisado/` | Modelos de aprendizaje no supervisado | Segunda parte de dataset de información de facturación en una tienda on-line de venta minorista | https://www.kaggle.com/code/marcinrutecki/clustering-methods-comprehensive-study/notebook |
| `basic2.csv` | `ml-no-supervisado/` | Modelos de aprendizaje no supervisado | Ejemplo de distribución de datos específico para pruebas de algoritmos de clustering | https://www.kaggle.com/code/marcinrutecki/clustering-methods-comprehensive-study/notebook |
| `blob.csv` | `ml-no-supervisado/` | Modelos de aprendizaje no supervisado | Ejemplo de distribución de datos específico para pruebas de algoritmos de clustering | https://www.kaggle.com/code/marcinrutecki/clustering-methods-comprehensive-study/notebook |
| `boxes3.csv` | `ml-no-supervisado/` | Modelos de aprendizaje no supervisado | Ejemplo de distribución de datos específico para pruebas de algoritmos de clustering | https://www.kaggle.com/code/marcinrutecki/clustering-methods-comprehensive-study/notebook |
| `dart.csv` | `ml-no-supervisado/` | Modelos de aprendizaje no supervisado | Ejemplo de distribución de datos específico para pruebas de algoritmos de clustering | https://www.kaggle.com/code/marcinrutecki/clustering-methods-comprehensive-study/notebook |
| `outliers.csv` | `ml-no-supervisado/` | Modelos de aprendizaje no supervisado | Ejemplo de distribución de datos específico para pruebas de algoritmos de clustering | https://www.kaggle.com/code/marcinrutecki/clustering-methods-comprehensive-study/notebook |
| `spiral2.csv` | `ml-no-supervisado/` | Modelos de aprendizaje no supervisado | Ejemplo de distribución de datos específico para pruebas de algoritmos de clustering | https://www.kaggle.com/code/marcinrutecki/clustering-methods-comprehensive-study/notebook |

## Uso desde Colab

```python
import pandas as pd

url = "https://raw.githubusercontent.com/henrypaulett/upc-datasets-docencia/refs/heads/main/ml-supervisado-regresion/winequality.csv"
df = pd.read_csv(url)
```

## Notas

- Datasets con fines exclusivamente educativos. Ninguno contiene datos reales de pacientes 
  ni información institucional sensible.
- Si un dataset no es de elaboración propia, se indica la fuente en la columna correspondiente 
  de la tabla.
