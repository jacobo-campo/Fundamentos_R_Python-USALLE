# Módulo de R

## Presentación

Este módulo introduce el uso de **R** como lenguaje de programación para el análisis de datos.

R es ampliamente utilizado en estadística, econometría, ciencia de datos, investigación social, economía, finanzas, salud pública y evaluación de políticas. Su principal ventaja es que permite trabajar de manera reproducible: desde la importación de datos hasta la generación de tablas, gráficos y resultados.

En este módulo se parte desde los fundamentos del lenguaje y se avanza hacia tareas básicas de análisis de información.

---

## Objetivo del módulo

Desarrollar habilidades básicas en el uso de R para importar, organizar, transformar, analizar y visualizar datos.

---

## Resultados de aprendizaje

Al finalizar este módulo, el estudiante podrá:

- Reconocer el entorno de trabajo de R y RStudio.
- Crear objetos y trabajar con distintos tipos de datos.
- Utilizar vectores, matrices, listas y data frames.
- Importar bases de datos en diferentes formatos.
- Realizar operaciones básicas de limpieza de datos.
- Calcular estadísticas descriptivas.
- Construir gráficos básicos.
- Escribir scripts ordenados y reproducibles.

---

## Contenido general

### 1. Introducción a R

- ¿Qué es R?
- ¿Qué es RStudio?
- Instalación de R y RStudio.
- Consola, script y entorno de trabajo.
- Directorio de trabajo.
- Comentarios en el código.

### 2. Objetos y tipos de datos

- Creación de objetos.
- Números.
- Texto.
- Variables lógicas.
- Valores perdidos.
- Operadores básicos.

### 3. Estructuras de datos

- Vectores.
- Matrices.
- Listas.
- Data frames.
- Factores.

### 4. Importación de datos

- Lectura de archivos `.csv`.
- Lectura de archivos `.xlsx`.
- Importación desde el portapapeles.
- Revisión inicial de una base de datos.

### 5. Manipulación de datos

- Selección de variables.
- Filtrado de observaciones.
- Creación de nuevas variables.
- Ordenamiento de datos.
- Agrupación de información.
- Resúmenes por grupos.

### 6. Estadística descriptiva

- Media.
- Mediana.
- Varianza.
- Desviación estándar.
- Mínimos y máximos.
- Tablas de frecuencia.
- Tablas cruzadas.

### 7. Visualización de datos

- Gráficos de dispersión.
- Gráficos de barras.
- Histogramas.
- Diagramas de caja.
- Gráficos de líneas.
- Introducción a `ggplot2`.

### 8. Ejercicios aplicados

- Limpieza de una base de datos.
- Análisis descriptivo.
- Construcción de gráficos.
- Interpretación de resultados.

---

## Paquetes sugeridos

Durante el módulo se utilizarán algunos de los siguientes paquetes:

```r
install.packages("tidyverse")
install.packages("readxl")
install.packages("writexl")
install.packages("janitor")
install.packages("skimr")
