# 📊 Análisis de Música y Salud Mental

📌 **Descripción del Proyecto**

Este proyecto consiste en la limpieza, preparación y visualización de los datos de la encuesta *“Music & Mental Health”*, que analiza cómo los hábitos musicales y preferencias afectan el bienestar emocional de los participantes. Los datos se transformaron y tradujeron al español, se crearon nuevas categorías de **grupo de edad** y **franjas horarias**, y se prepararon para análisis exploratorio y visualizaciones interactivas en Power BI, incluyendo mapas de calor generados con Python.

---

🎯 **Objetivos**

- Cargar y explorar los datos de la encuesta sobre música y salud mental.  
- Limpiar y transformar los datos para análisis posteriores.  
- Crear columnas calculadas para **grupo de edad** y **franja horaria**.  
- Traducir nombres de columnas y valores para facilitar la interpretación.  
- Preparar el dataset y generar visualizaciones interactivas en Power BI.  

---

🧪 **Metodología**

- Limpieza de datos y análisis exploratorio con Python (`pandas`, `numpy`).  
- Imputación de valores faltantes de BPM según promedio por género musical.  
- Eliminación de filas con datos irreparables.  
- Creación de columnas categóricas **Grupo de Edad** y **Franja horaria.**
- Traducción y homogeneización de nombres de columnas y valores al español.  
- Creación de visualizaciones interactivas y mapas de calor en Power BI.  
- Exportación del dataset limpio (`data_clear.csv`) listo para análisis y visualizaciones.

---

📁 **Archivos incluidos**

- `mxmh_survey_results.csv`: Dataset original de la encuesta.  
- `mxmh_survey_clean.ipynb`: Notebook en Python con limpieza, transformación y preparación de datos.  
- `data_clear.csv`: Dataset limpio y preparado para análisis y visualizaciones.  
- `Music & Mental Health.pbix`: Dashboard completo en Power BI con visualizaciones interactivas.  

---

🛠️ **Tecnologías utilizadas**

- Power BI  
- Python (`pandas`, `numpy`, `matplotlib`, `seaborn`)  
- Jupyter Notebook  

---

📌 **Conclusiones**

- La música tiende a **reducir los niveles de ansiedad, depresión, insomnio y TOC** en todos los casos.  
- Tocar un instrumento está asociado a una reducción de los síntomas, pero **componer música tiene un efecto aún más significativo**.  
- Los efectos se perciben de manera más intensa en los participantes de **18 a 22 años**, y menos en el rango de **40 a 46 años**.  
- La franja horaria donde se registra el mayor efecto emocional positivo es entre **16:00 y 20:00**.  
- Entre los géneros musicales, **el Rock** es el que más se asocia a niveles altos de efecto emocional positivo según la encuesta.

---

🚀 **Autor**: Iván García Raso  
🔗 GitHub: [IvanDataProjects](https://github.com/IvanDataProjects)  
🔗 LinkedIn: [Iván García Raso](https://www.linkedin.com/in/ivangarciaraso/)
