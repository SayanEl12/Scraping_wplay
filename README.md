# Pre and Post-Match Sports Data Mining Project

**Descripción del Proyecto:**
Este proyecto se centra en la extracción de datos de la plataforma de apuestas deportivas Wplay, tanto antes como después de la ejecución de los partidos. El objetivo principal es recopilar datos esenciales para realizar apuestas informadas y construir modelos de predicción futuros.

**Objetivos del Proyecto:**
Este proyecto se inicia como un experimento con la finalidad de desarrollar una base de datos de alta calidad para impulsar futuras predicciones y modelos de apuestas deportivas.

**Funcionalidades Principales:**
- Extracción de datos pre-partido y post-partido.
- Generación de dos tipos de archivos Excel: uno con datos antes de los partidos y otro con datos posteriores.
- Personalización de las ligas a analizar y los archivos Excel a generar.
- Fácil ejecución en entornos como Jupyter Notebook o Google Colab con acceso a Internet.

**Requisitos de Instalación:**
Solo se necesita un entorno de desarrollo compatible con Python 3.10.6, como Jupyter Notebook o Google Colab, además de acceso a Internet.

**Guía de Uso:**
1. Ejecuta las primeras cuatro casillas.
2. Luego, ejecuta una casilla que contiene dos listas: una con las URLs de las ligas que deseas analizar y otra con los nombres de los archivos Excel que deseas crear.
3. A continuación, ejecuta una casilla para el pre-partido utilizando la clase `Excel_pre_partido`, proporcionando la lista de URLs como parámetro.
4. Por último, ejecuta una casilla para el post-partido utilizando la clase `Excel_pos_partido`, proporcionando la lista de URLs y el archivo Excel como parámetros.

**Ejemplos de Uso:**
- Para el pre-partido: `PRE_PARTIDO = Excel_pre_partido(urls=URLs)`
- Para el post-partido: `POS_PARTIDO = Excel_pos_partido(urls=URLs, excel=excel)`

**Contribuciones:**
El proyecto ha sido desarrollado en su totalidad por el creador y no se están aceptando contribuciones externas en este momento.

**Licencia:**
Este proyecto actualmente no cuenta con una licencia específica.

**Contacto:**
Para cualquier pregunta o consulta, puedes contactar al creador a través del correo electrónico: the12sayan@gmail.com

**Estado del Proyecto:**
El proyecto se encuentra en una fase beta y se actualiza de forma continua para mejorarlo.

**Prerrequisitos Técnicos:**
Se requieren conocimientos muy básicos en Python y una instalación de Python 3.10.6 para utilizar este proyecto.