📊 Análisis de Comportamiento del Cliente: ConnectaTel
Este repositorio contiene un análisis integral de los patrones de consumo de los clientes de ConnectaTel, una empresa de telecomunicaciones en Latinoamérica. El proyecto abarca desde la limpieza de datos hasta la segmentación estratégica para optimizar la oferta comercial de la compañía.

🎯 Objetivo del Proyecto
Evaluar el comportamiento de los usuarios registrados hasta el año 2024, identificando perfiles de consumo, detectando comportamientos atípicos y proponiendo mejoras en los planes actuales (Surf y Ultimate) para aumentar la retención y rentabilidad.

📂 Datasets Utilizados
El análisis se basa en tres fuentes de datos principales:

plans.csv: Parámetros de los planes (precio base, minutos/mensajes incluidos y costos por excedentes).

users.csv: Datos demográficos (edad, ciudad, fecha de registro, plan y estado de churn).

usage.csv: Registro detallado de la actividad real (llamadas, duración y mensajes enviados).

🛠️ Etapas del Análisis
El flujo de trabajo se divide en las siguientes fases:

Exploración y Limpieza de Datos:

Tratamiento de valores nulos y duplicados.

Saneamiento de la columna age (manejo de valores centinela -999).

Conversión de tipos de datos para análisis temporal.

Análisis Estadístico Descriptivo:

Resumen de métricas clave por usuario y plan.

Análisis de distribución porcentual de la base de clientes.

Visualización de Datos:

Histogramas de edad y niveles de consumo.

Identificación visual de sesgos en los datos.

Detección de Outliers:

Uso del método del Rango Intercuartílico (IQR) y BoxPlots para identificar "Heavy Users".

Segmentación de Clientes:

Por Uso: Clasificación en 'Bajo', 'Medio' y 'Alto uso'.

Por Edad: Segmentación en 'Joven', 'Adulto' y 'Adulto Mayor'.

🚀 Cómo ejecutar el proyecto
Para reproducir este análisis en tu entorno local o en la nube:

Opción A: Google Colab (Recomendado)
Haz clic en el botón "Open in Colab" (si lo agregas al notebook) o sube el archivo .ipynb directamente.

Sube los archivos .csv a la sección de archivos de la barra lateral izquierda.

Ejecuta las celdas de forma secuencial.

Opción B: Entorno Local
Clona este repositorio:

Bash
git clone https://github.com/tu-usuario/nombre-del-repo.git
Instala las librerías necesarias:

Bash
pip install pandas numpy matplotlib seaborn
Abre el archivo telecom_analysis.ipynb con Jupyter Notebook o VS Code.

📋 Guía de Reproducción
Carga: Asegúrate de que los datasets estén en la misma carpeta que el notebook.

Limpieza: Ejecuta primero las secciones de tratamiento de nulos para evitar errores en los gráficos.

Visualización: Los gráficos están configurados con seaborn para una interpretación clara.

💡 Principales Hallazgos (Insight Ejecutivo)
Patrones de Consumo: La mayoría de las variables de consumo presentan un sesgo a la derecha, lo que indica que una minoría de usuarios genera la mayor parte de los excedentes.

Decisión sobre Outliers: Se mantuvieron los valores extremos en el análisis ya que representan comportamientos de uso reales y críticos para la facturación.

Segmentación: Se detectó una oportunidad en los usuarios de "Alto Uso" que actualmente están en el plan Surf, quienes podrían beneficiarse de una migración al plan Ultimate.

Autor: Sergio Jose Galindo Hamsho

Contacto: www.linkedin.com/in/sergio-galindo-68a7a4383
