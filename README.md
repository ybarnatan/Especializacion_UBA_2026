<!-- Banner Section -->
<div align="center">
  <img src="img/banner_DM_UBA.png" width="600" height="500" alt="banner" />

  
  <h1> Cancelaciones hoteleras, ganancia económica y segmentación de riesgo: un enfoque de machine learning para la gestión de liquidez. </h1>
  <h2> Autor: Dr. Yair B. Barnatan </h2>
 
<h4>Tesis presentada para optar por el título de Especialista en Explotación de Datos y Descubrimiento de Conocimiento.</h4>
<h5> UNIVERSIDAD DE BUENOS AIRES</h5>   

</div>


  
## ✍️ **Autor**  

**Dr. Yair B. Barnatan**

Cientifico de datos y biologo, apasionado por la resolución de problemas combinando rigor cuantitativo, tecnologias modernas y con un enfoque práctico de negocio.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Yair_Barnatan-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/yair-barnatan/)




## 📄 Disponibilidad del manuscrito

El texto completo de la tesis estará disponible próximamente en la biblioteca digital de la Facultad.

Asimismo, los interesados en consultar una copia en formato digital pueden solicitar el documento directamente a través del contacto con el autor.



## 🎯 Objetivo del proyecto

El objetivo principal de este proyecto es analizar los patrones de reserva hotelera, identificar las variables clave asociadas a las tasas de cancelación y construir modelos de aprendizaje automático (machine learning) para predecir las reservas que seran canceladas. Todo esto se analiza bajo una optica de negocio en contextos de _turnaround_.


## 📁 Estructura del repositorio

Este repositorio contiene el proyecto completo de ciencia de datos desarrollado para el desarrollo de esta tesis. El mismo cubre el preprocesamiento de datos, análisis exploratorio, ingeniería de características y modelado predictivo de cancelaciones de reservas.


| Notebook                       | Link                                  |
|-------------------------------------|---------------------------------------------|
| Preprocesamiento y EDA                 | [![Project 1](https://img.shields.io/badge/Preprocesamiento_y_EDA-violet)](https://github.com/ybarnatan/Especializacion_UBA_2026/blob/main/Notebooks/01_Preprocessing_and_EDA.ipynb)|
| Ingenieria de atributos                        | [![Project 2](https://img.shields.io/badge/Feature_Engeneering-green)](https://github.com/ybarnatan/Especializacion_UBA_2026/blob/main/Notebooks/02_FeatEng.ipynb) |
| Modelado de datos            | [![Project 3](https://img.shields.io/badge/Modelado-orange)](https://github.com/ybarnatan/Especializacion_UBA_2026/blob/main/Notebooks/03_Modelling.ipynb) |



## ⚙️ Configuración del entorno virtual e instalación
Seguir estos pasos utilizando PowerShell para configurar el entorno e instalar las dependencias desde el directorio Requirements/:

1. Navegar al directorio raíz del proyecto: `cd "Proyecto Hoteles`
2. Crear el entorno virtual: `py -m venv Hotel.venv`
3. Activar el entorno virtual: `Hotel.venv\Scripts\activate`
4. Instalar paquetes requeridos en cada requirement para cada notebook:  `pip install -r Requirements/<nombre_del_archivo_req>.txt`


## 📊 Fuente de datos
El análisis utiliza el Hotel Booking Demand Dataset, publicado originalmente por Nunes, Antonio, Almeida & Nunes (2019) en Data in Brief (Vol. 22).
