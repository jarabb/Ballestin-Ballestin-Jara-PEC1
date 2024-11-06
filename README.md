# Ballestin-Ballestin-Jara-PEC1
M0.157 - Análisis de datos ómicos - PEC1

## Descripción general del dataset
Este conjunto de datos proviene del estudio "Metabotypes of response to bariatric surgery independent of the magnitude of weight loss". El dataset contiene información clínica y metabolómica de 39 pacientes en 5 puntos temporales diferentes.
Los datos originales fueron descargados del repositorio de github https://github.com/nutrimetabolomics/Metabotyping2018.

## Otros archivos incluidos en este repositorio
- `SummarizedExperiment.Rda`: Objeto contenedor SummarizedExperiment con los datos y los metadatos en formato binario.
- `Ballestin-Ballestin-Jara-PEC1.pdf`: Informe con la descripción del proceso de realización de esta PEC.
- `Ballestin-Ballestin-Jara-PEC1.Rmd`: Eñl código en R incluído en el informe.
  
## Archivos en la carpeta "data"
- `DataValues_S013.csv`: Contiene los valores clínicos y metabolómicos de las muestras.
- `DataInfo_S013.csv`: Metadatos sobre las columnas en `DataValues_S013.csv`.
- `AAInformation_S006.csv`: Información adicional sobre los metabolitos.
- `datos.txt`: Los datos de `DataValues_S013.csv` en formato texto.

## Variables
- Número total de variables en los datos: 695
- Datos demográficos/clínicos: 5 variables (SUBJECTS, SURGERY, AGE, GENDER, Group)
- Datos medidos en diferentes momentos: 690 variables
