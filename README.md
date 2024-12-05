# Requisitos y Descripción de Instalaciones para Análisis de Datos en R

## 1. Introducción
Se describe las bibliotecas y configuraciones necesarias para ejecutar un análisis de datos utilizando algoritmos como **Apriori**, **FP-Growth**, y **K-means clustering** en R. Se incluyen las descripciones de las funcionalidades de los algoritmos y los pasos requeridos para implementar la solución.

---

## 2. Instalación de Bibliotecas

Se requiere la instalación de varias bibliotecas para el análisis y la minería de datos:

### 2.1. Dependencias
1. **Java**: Necesario para paquete de rJava.


### 2.2. Bibliotecas en R
Instalar y cargar las siguientes bibliotecas en R:

install.packages(c("caret", "arules", "Matrix", "readxl", "tibble", "rpart", "rpart.plot", "randomForest"))


### 2.3. Bibliotecas en python
generar un entorno virtual en la carpeta **python -m venv entorno**

activar el entorno ** .\entorno\Scripts\activate** o ** activarlo en el editor de codigo **

se instalan todas las librerias necesarias con ** pip install -r requirements.txt **