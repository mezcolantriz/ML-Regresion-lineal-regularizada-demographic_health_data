# Análisis de Datos Socio-Demográficos y Recursos de Salud en EE. UU.

Este repositorio contiene un proyecto de análisis de datos que investiga la relación entre los recursos sanitarios y los datos socio-demográficos a nivel de condado en los Estados Unidos (2018-2019).

## Descripción del Proyecto

El objetivo principal es determinar si existe alguna relación entre los recursos de salud y los factores socio-demográficos de los condados estadounidenses. Para ello, se ha trabajado con un conjunto de datos que incluye diversas variables, tanto demográficas como relacionadas con la salud.

El flujo del proyecto se estructura en los siguientes pasos:

1. **Carga de Datos:**  
   Se utiliza el conjunto de datos `demographic_health_data.csv`, disponible en:  
   [https://raw.githubusercontent.com/4GeeksAcademy/regularized-linear-regression-project-tutorial/main/demographic_health_data.csv](https://raw.githubusercontent.com/4GeeksAcademy/regularized-linear-regression-project-tutorial/main/demographic_health_data.csv)  
   Se incluye el código necesario para cargar y leer los datos.

2. **Análisis Exploratorio de Datos (EDA):**  
   Se realiza un análisis exploratorio completo para identificar las variables relevantes y descartar aquellas que no aportan información. Se aplican técnicas de limpieza de datos y visualización, además de una adecuada división del conjunto de datos en train y test.

3. **Construcción del Modelo de Regresión:**  
   - Se implementa inicialmente un modelo de regresión lineal.
   - A continuación, se construye un modelo Lasso usando los mismos datos y atributos por defecto.
   - Se comparan los resultados de ambos modelos, haciendo especial énfasis en la evolución del coeficiente R² a medida que se modifica el hiperparámetro de Lasso (probando valores de 0.0 hasta 20).

4. **Optimización del Modelo:**  
   Si los resultados del modelo Lasso no son satisfactorios, se aplican técnicas de optimización vistas en el curso para mejorar el rendimiento del modelo.

## Requisitos Previos

- **Python:** 3.11 o superior.
- **Pip:** Para la instalación de paquetes.

## Instalación

1. Clona el repositorio en tu máquina local:
   ```bash
   git clone <URL-del-repositorio>
2. Navega al directorio del proyecto
   bash
   cd <nombre-del-directorio-del-proyecto>

3. Instala los paquetes necesarios
   bash
   pip install -r requirements.txt

4. Uso
   
 Abre el Notebook incluido en el repositorio para visualizar el análisis completo y el desarrollo de los modelos:
 El Notebook contiene secciones para cargar datos, realizar el EDA, entrenar y evaluar los modelos de regresión.
 Sigue las instrucciones y ejecuta las celdas paso a paso para replicar el análisis.
   
  
  Contribuciones
  Si deseas contribuir a este proyecto, por favor, haz un fork del repositorio y envía un pull request con tus mejoras.

  Licencia
  Este proyecto se distribuye bajo la Licencia MIT.



   
