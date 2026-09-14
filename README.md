# Análisis de Airbnb en Bogotá

Proyecto final de la asignatura Data Experience (Universidad EAN). Análisis de datos sobre
alojamientos de Airbnb en Bogotá: limpieza, análisis estadístico, visualización y modelos
predictivos.

## 🎯 Objetivo
¿Qué características de un listado de Airbnb en Bogotá predicen mejor su calificación
general y su nivel de ocupación, según propiedades activas en los últimos 12 meses?

Se analizan principalmente: precio, ocupación, calificación, tipo de propiedad, ubicación,
amenidades y características del anfitrión.

## 📂 Estructura del repositorio
| Archivo | Descripción |
|---|---|
| `Bogotá_Airbnb_Informe.html` | Informe completo del proyecto (código + análisis + resultados) |
| `Bogotá_Airbnb_ProyectoFinal.ipynb` | Notebook de Google Colab con el código original, ejecutable |
| `Bogotá_Airbnb_PresentacionFinal.pdf` | Diapositivas de la sustentación |

## 🔎 Metodología
1. Exploración inicial de los datos.
2. Limpieza y transformación del dataset.
3. Análisis estadístico descriptivo.
4. Visualización de los datos.
5. Pruebas estadísticas.
6. Construcción de modelos predictivos.
7. Evaluación de resultados.

## 🤖 Modelos
- **Regresión lineal múltiple** para predecir la calificación general (rating): R² = 0.111, MAE = 0.242.
- **Regresión logística multinomial** para clasificar el nivel de ocupación en Baja, Media y Alta: exactitud = 82.4%.

## 🛠️ Tecnologías
Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn — Google Colab / Jupyter Notebook.

## ▶️ Ejecución
1. Descargar el dataset original desde [Inside Airbnb](https://insideairbnb.com/es/get-the-data/?hl=es-AR) (Bogotá, listing details).
2. Abrir `Bogotá_Airbnb_ProyectoFinal.ipynb` en Google Colab.
3. Montar Google Drive y ajustar la ruta del archivo CSV en la primera celda.
4. Ejecutar todas las celdas en orden (Entorno de ejecución → Ejecutar todas).

## 📊 Resultados
El análisis muestra que el desempeño de una propiedad no depende únicamente del precio.
Factores como la ubicación, el tipo de alojamiento, las amenidades y las características
del anfitrión (ej. ser superhost) también están relacionados con su calificación y nivel
de ocupación. La ocupación resultó considerablemente más predecible (82.4% de exactitud)
que la calificación general (R² = 0.111), sugiriendo que el desempeño comercial depende
más de decisiones controlables por el anfitrión que de la satisfacción subjetiva del huésped.

El análisis completo, código, gráficos y resultados se encuentran en el informe y el notebook.

## 📚 Fuente de datos
[Inside Airbnb](https://insideairbnb.com/es/get-the-data/?hl=es-AR) — datos públicos de listados de Airbnb en Bogotá.

## 👥 Autores
Data Experience G4
- Eimy Nicolle Rubio
- Laura Torres
- Juan Esteban Melo
- Juan Serrano
