# Clasificación de Células Tumorales (Benignas / Malignas)

Este proyecto implementa un modelo de Machine Learning para la clasificación de células tumorales en benignas o malignas utilizando aprendizaje supervisado.

## 📌 Descripción
El objetivo del proyecto es construir un modelo de clasificación que ayude a detectar si una célula tumoral es benigna o maligna a partir de sus características. Para ello, se utiliza un conjunto de datos que contiene diversas medidas extraídas de imágenes digitales de núcleos celulares.

## 🛠️ Tecnologías y Herramientas
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

## 📂 Estructura del Proyecto
```
├── Clasificación_celulas_T.ipynb  # Notebook con el desarrollo del modelo
├── README.md                      # Documentación del proyecto
```

## 📊 Dataset
El dataset utilizado en este proyecto proviene de una fuente pública de datos médicos. Contiene atributos relacionados con la morfología de las células tumorales, como:
- Radio de la célula
- Textura
- Perímetro
- Área
- Suavidad
- Concavidad
- Simetría, entre otros.

## 🔎 Flujo de Trabajo
1. **Carga y exploración de datos:** Inspección y limpieza del conjunto de datos.
2. **Análisis exploratorio:** Visualización de distribuciones y correlaciones entre variables.
3. **Preprocesamiento:** Normalización, división en conjuntos de entrenamiento y prueba.
4. **Entrenamiento del modelo:** Implementación de modelos de clasificación (Random Forest, SVM, etc.).
5. **Evaluación:** Métricas como precisión, recall, F1-score y matriz de confusión.
6. **Guardado del modelo:** Exportación para su posterior uso.

## 📈 Resultados
El modelo entrenado alcanzó una precisión del 94% en el conjunto de prueba, con una buena capacidad de generalización en la clasificación de células tumorales.


## 📜 Licencia
Este proyecto está bajo la licencia MIT.


