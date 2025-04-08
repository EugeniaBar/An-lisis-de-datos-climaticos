# Análisis de Series Temporales de Datos Climáticos: Temperatura Global y Gases de Efecto Invernadero

### 🎯 Objetivo del proyecto

Este proyecto analiza la relación entre la temperatura global y las concentraciones de metano (CH₄) y dióxido de carbono (CO₂), con el fin de:

- Estudiar su evolución temporal a través de series de tiempo.
- Predecir futuras temperaturas globales.
- Detectar anomalías o patrones estacionales.
- Explorar correlaciones entre los gases y la temperatura global.

📊 Fuente de los datos:  
https://climate.nasa.gov/

---

### 🧠 Resumen del proyecto

El cambio climático es uno de los retos más urgentes del siglo XXI, impulsado en gran parte por el aumento de los gases de efecto invernadero (GEI). En este análisis, se utilizaron tres conjuntos de datos públicos de la NASA sobre:

- Temperatura global (datos anuales).
- Dióxido de carbono (CO₂, datos mensuales).
- Metano (CH₄, datos mensuales).

A través del análisis de series temporales, se estudiaron tendencias, estacionalidades y la variabilidad mensual y anual de estos gases.

Se entrenó un modelo de predicción **Random Forest** para estimar la temperatura global, logrando un **R² = 0.9852**, lo que indica un excelente rendimiento. La validación cruzada mostró un modelo estable y confiable, con baja variabilidad en su desempeño.

#### 🔍 Principales hallazgos:

- **Crecimiento sostenido** de CO₂ y CH₄ en las últimas décadas.
- **Correlación positiva** entre estos gases y la temperatura global.
- El CO₂ muestra un crecimiento constante; el CH₄ es más **volátil y estacional**.
- Se visualizan patrones estacionales claros en ambas series de gases.
  
Este proyecto ofrece evidencia de la estrecha relación entre las emisiones de gases y el calentamiento global, destacando la importancia de seguir monitoreando estas variables para entender y mitigar el cambio climático.

---

### ⚙️ Tecnologías utilizadas

- Python
- Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- Jupyter Notebook

![image](https://github.com/user-attachments/assets/9cba2818-f5d3-4597-a70b-f694a8b6a41f)
