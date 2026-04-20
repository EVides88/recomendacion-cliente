# Predicción de Recomendación de Productos

## Descripción del Proyecto

Este proyecto construye un pipeline de aprendizaje automático para predecir si un cliente recomendará un producto basado en texto de reseñas, variables numéricas y categóricas.

El pipeline integra el preprocesamiento de datos y el modelo en un solo flujo utilizando scikit-learn.

---

## Archivos del Repositorio

- `starter.ipynb`: Notebook principal con todo el desarrollo del proyecto
- `data/`: Carpeta que contiene el dataset utilizado (`reviews.csv`)

---

## Cómo Ejecutar el Proyecto

1. Abrir el notebook `starter.ipynb`
2. Ejecutar las celdas en orden
3. El modelo se entrena y evalúa automáticamente

---

## Dependencias

Este proyecto utiliza:

- pandas
- numpy
- scikit-learn

Se pueden instalar con:

pip install pandas numpy scikit-learn

---

## Pipeline del Modelo

El pipeline incluye:

- Procesamiento de texto con TF-IDF
- Escalado de variables numéricas
- Codificación de variables categóricas
- Modelo de regresión logística

Se utiliza `ColumnTransformer` para manejar diferentes tipos de datos.

---

## Resultados

El modelo alcanza aproximadamente:

- Accuracy: 88%
- Buen desempeño en la clase positiva
- Rendimiento menor en la clase negativa debido al desbalance de datos

---

## Autor

Proyecto desarrollado por Ernesto Ponce