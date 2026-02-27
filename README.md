📊 Análisis de Comportamiento del Cliente: ConnectaTel 2024
Este proyecto realiza un análisis exhaustivo de los patrones de consumo de los usuarios de la empresa de telecomunicaciones ConnectaTel. El objetivo principal es evaluar la rentabilidad de los planes actuales (Surf y Ultimate) y proponer estrategias basadas en datos para mejorar la retención y captación de clientes.

🎯 Objetivo del Proyecto
Identificar perfiles de consumo, detectar comportamientos atípicos (outliers) y segmentar a la base de usuarios para generar recomendaciones estratégicas que optimicen la oferta comercial de la empresa.

📂 Datasets Utilizados
El análisis se basa en tres archivos de datos clave:

plans.csv: Detalles técnicos de los planes (costos mensuales, límites de minutos/mensajes y tarifas por excedentes).

users.csv: Información demográfica de los clientes (edad, ciudad, fecha de registro y plan contratado).

usage.csv: Registro detallado de la actividad real (cantidad de llamadas, duración en minutos y mensajes enviados).

🛠️ Etapas del Análisis
El proyecto sigue un flujo de trabajo de Ciencia de Datos estándar:

Limpieza y Preprocesamiento: Tratamiento de valores nulos, corrección de tipos de datos y manejo de valores centinela (como edades en -999).

Análisis Estadístico: Resumen descriptivo de las variables numéricas y categóricas.

Visualización de Distribuciones: Uso de histogramas para entender la forma de los datos (minutos, mensajes y edad).

Detección de Outliers: Identificación de "Heavy Users" mediante el método del Rango Intercuartílico (IQR) y diagramas de caja (Boxplots).

Segmentación de Clientes: Clasificación de usuarios por nivel de uso (Bajo, Medio, Alto) y por rango etario (Joven, Adulto, Adulto Mayor).

Insights Ejecutivos: Traducción de hallazgos técnicos en recomendaciones de negocio.

🚀 Cómo Ejecutar el Proyecto
Para visualizar y ejecutar este análisis, puedes utilizar Google Colab (recomendado) o un entorno local de Jupyter.

Opción 1: Google Colab
Sube el archivo .ipynb a tu Google Drive.

Haz clic derecho sobre el archivo y selecciona Abrir con > Google Colaboratory.

Asegúrate de subir los archivos .csv a la sesión de Colab (icono de carpeta a la izquierda) para que el código pueda leerlos.

Opción 2: Local (Jupyter Notebook)
Necesitarás tener instalado Python y las siguientes librerías:

Bash
pip install pandas numpy seaborn matplotlib
Luego, ejecuta el comando jupyter notebook en tu terminal dentro de la carpeta del proyecto.

📋 Guía de Reproducción
Para obtener los mismos resultados presentados en el análisis, sigue este orden:

Carga de Datos: Asegúrate de que los archivos CSV tengan los nombres correctos mencionados en la sección de Datasets.

Ejecución Secuencial: Ejecuta las celdas del notebook en orden, desde la importación de librerías hasta las conclusiones.

Validación de Rutas: Si los archivos están en una carpeta específica, ajusta la ruta en la función pd.read_csv().

💡 Recomendaciones del Analista
Identificación de Oportunidades: El análisis revela que el plan Surf es el mayor generador de ingresos por excedentes debido a sus límites bajos.

Estrategia: Se recomienda un plan intermedio para evitar la fuga de clientes que exceden constantemente sus límites pero no desean el costo del plan Ultimate.

Contribuciones: Las sugerencias y comentarios son bienvenidos. Si encuentras un hallazgo interesante, ¡abre un Issue!
