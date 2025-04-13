# Análisis de Series Temporales de Datos Climáticos: Temperatura Global y Gases de Efecto Invernadero

### Informe Completo del projecto: 
https://github.com/EugeniaBar/An-lisis-de-datos-climaticos/blob/main/An%C3%A1lisis%20de%20Series%20Temporales%20de%20datos%20climaticos.pdf

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

"Este proyecto fue desarrollado con un fin estrictamente educativo, buscando aprender y aplicar técnicas de análisis de datos a información climática real. Se utilizaron datos de concentraciones de metano y dióxido de carbono, así como registros de temperatura global, para explorar las relaciones entre estos factores y el fenómeno del calentamiento global. Dado el carácter educativo del proyecto, se reconoce que los análisis y conclusiones presentados podrían contener errores o interpretaciones limitadas. El objetivo principal fue practicar y mejorar mis habilidades en el manejo y análisis de datos, utilizando un tema de relevancia científica y social."



![image](https://github.com/user-attachments/assets/9cba2818-f5d3-4597-a70b-f694a8b6a41f)

![3d5f13a1-3e17-4f51-ae65-6b35f708e035](https://github.com/user-attachments/assets/0388ac5f-cb74-4093-acca-482d16086c6f)


