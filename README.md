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

```r
install.packages(c("arules", "Matrix", "readxl", "tibble", "ggplot2"))
library(arules)
library(Matrix)
library(readxl)
library(tibble)
library(ggplot2)
