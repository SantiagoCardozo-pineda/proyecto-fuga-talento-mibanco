# 📊 Modelo Predictivo de Fuga de Talento – MiBanco Perú

Este proyecto fue desarrollado como trabajo final del máster en Data Science y Big Data de IEBS. El objetivo fue construir un modelo predictivo para identificar empleados con alto riesgo de fuga en áreas tecnológicas de MiBanco Perú, y proponer estrategias efectivas de retención basadas en análisis de datos.

---

## 🧠 Equipo
Proyecto realizado por:
- Ferney Santiago Cardozo Pineda
- José Antonio Álvarez Guerrero
- Robinson Josué Mayta Calderón
- Luis David Rodríguez Díaz
- Juan Gerardo Rodríguez Monrroy

---

## 🧾 Contenido del proyecto
- 📄 Informe completo: [`TF_Grupo14_011024.pdf`](./TF_Grupo14_011024.pdf)
- 🧼 Código de limpieza de datos: [Ver en Google Colab](https://colab.research.google.com/drive/1HekPqOBp4P-IEK6Hj9t_b80Lctqn1Roh?usp=sharing)
- 🤖 Código del modelo predictivo: [Ver en Google Colab](https://colab.research.google.com/drive/1sA9j-ZF9kV_vJltVYfxCofI8RRD83WIm?usp=drive_link)
- ⚠️ Por razones de confidencialidad, las bases de datos originales utilizadas en este proyecto no están disponibles públicamente.  
Sin embargo, puedes revisar el informe completo y el código del modelo en los enlaces proporcionados.


---

## 🧰 Herramientas y tecnologías usadas
- Python (pandas, sklearn, xgboost, shap)
- Google Colab
- Power BI
- AWS (para almacenamiento seguro de datos)
- Jupyter Notebook

---

## 📊 Resultados del modelo

- Se utilizó un conjunto de datos de más de **600.000 registros**, depurado a **2.249 registros únicos relevantes** de colaboradores del área tecnológica.
- Se aplicaron modelos de **Regresión Logística** y **XGBoost**, alcanzando una **precisión AUC de 0.87**, demostrando una capacidad sólida para predecir la fuga de talento sin sobreajuste.
- El modelo identificó correctamente al **80% de los empleados cesados** en la base de prueba.
- Las variables con mayor influencia fueron:
  - Rango salarial
  - División
  - Tipo de contrato
  - Tiempo en el puesto
- Se calculó la **rentabilidad individual** de cada empleado, identificando casos con alto valor estratégico para priorizar retención.

---

## ✅ Conclusiones

- La **rotación de talento digital** es un problema real y crítico para empresas financieras como MiBanco, que afecta productividad, continuidad y costos.
- El modelo permite a RR.HH. **anticipar salidas** y actuar con estrategias de retención enfocadas en colaboradores clave.
- De los casos identificados como potenciales fugas, solo **14 empleados** resultaron ser altamente rentables, lo que permite **focalizar recursos** con inteligencia.
- El análisis demuestra que incluso con datos limitados, el **machine learning puede aportar insights accionables** a la gestión del talento humano.

---

## 🔍 Recomendaciones futuras

- Integrar el modelo a sistemas de RR.HH. para monitoreo continuo y decisiones en tiempo real.
- Incluir nuevas variables como satisfacción laboral, desempeño y evolución salarial.
- Evaluar modelos adicionales (Random Forest, Redes Neuronales) si se amplía la base de datos.
- Desarrollar dashboards visuales con Power BI para facilitar el uso del modelo por parte de áreas no técnicas.

