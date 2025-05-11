README - Análisis de Evasión de Clientes (Churn) - TelecomX

Este proyecto tiene como objetivo analizar los factores que influyen en la cancelación de servicios por parte de los clientes (churn) en la empresa TelecomX, utilizando técnicas de análisis exploratorio de datos (EDA), visualizaciones y exportación de informes.

🚀 Objetivos del Proyecto

Comprender el comportamiento de cancelación (churn) de clientes.

Identificar patrones por género, tipo de contrato, cargo mensual y servicios contratados.

Visualizar correlaciones entre variables.

Generar un informe automatizado (PDF) con gráficos e insights.

⚖️ Tecnologías Usadas

Python 3

Pandas para manipulación de datos

Seaborn / Matplotlib para visualizaciones

Plotly (opcional) para dashboards interactivos

ReportLab para generación de informes en PDF

⚙️ Instalación

Clona este repositorio o descarga el proyecto:

git clone (https://github.com/Vanne-Rbg/Challenge_TelecomX/new/main?filename)

Crea un entorno virtual (opcional pero recomendado):

python -m venv venv
source venv/bin/activate  # o venv\Scripts\activate en Windows

Instala las dependencias:

pip install -r requirements.txt

📂 Archivos Principales

TelecomX_Data.json: Base de datos original.

Telecom-X_Vanne.ipynb: Notebook con el análisis completo.

graficos_churn/: Carpeta con los gráficos generados.

informe_churn_telecom.pdf: Informe final automatizado.

README.md: Este archivo explicativo.

▶️ Cómo Ejecutar el Proyecto

Abre el archivo Telecom-X_Vanne.ipynb en Jupyter o Google Colab.

Ejecuta las celdas paso a paso:

Limpieza y preparación de datos.

Visualización de patrones de churn.

Cálculo de correlaciones.

Generación y exportación del informe en PDF.

⚠️ Posibles Problemas

Si los gráficos no se muestran en Colab, asegúrate de usar plt.show() al final.

Verifica que TelecomX_Data.json esté en el mismo directorio del notebook.

Algunas columnas pueden requerir limpieza adicional si el archivo cambia.

📈 Contribuciones

Las contribuciones son bienvenidas. Puedes abrir un issue o hacer un pull request para mejoras, correcciones o nuevas funcionalidades.

🙏 Agradecimientos

Gracias por revisar este proyecto. Esperamos que te ayude a comprender y reducir el churn en tu organización.
