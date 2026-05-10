# 🏥 Predicción de Grupos Relacionados por Diagnóstico (GRD) mediante Machine Learning

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.3-orange)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00)
![NLP](https://img.shields.io/badge/NLP-CountVectorizer-green)

## 📂 Descripción de Archivos

A continuación se detalla el contenido de los archivos principales de este repositorio:

- **`Análisis Exploratorio.ipynb`**: Análisis y visualización de la distribución clínica de los pacientes.
- **`Código de MLP.ipynb`**: Preprocesamiento de texto médico (NLP con `CountVectorizer`), diseño, entrenamiento y evaluación del modelo Perceptrón Multicapa.
- **`dataset_elpino.csv`**: Conjunto de datos base con registros clínicos y demográficos anonimizados de las admisiones del Hospital El Pino.

## 📝 Resumen

Este proyecto aborda el desarrollo de un modelo predictivo basado en aprendizaje automático para anticipar la clasificación **GRD (Grupos Relacionados por Diagnóstico)** de un paciente al momento de su ingreso hospitalario. 

Utilizando datos reales, el estudio se enfoca en procesar texto clínico no estructurado mediante técnicas de Procesamiento de Lenguaje Natural (NLP). Estas matrices de datos, junto con el perfil demográfico, alimentan arquitecturas de Redes Neuronales (MLP) optimizadas para manejar la alta dimensionalidad y el desbalance de clases. El modelo final logró una exactitud cercana al 90%, demostrando que la predicción temprana del GRD es viable y representa una herramienta clave para optimizar la asignación de recursos, camas y presupuestos en la gestión de salud.

## 🎓 Integrantes y Curso

* **Asignatura:** Aprendizaje de Máquina 
* **Profesor:** Pablo Hernán Schwarzenberg Riveros
* **Integrantes:**
  * Vicente Blaessinger Ebers
  * Nicolás Antonio Cabrera Valdivia
  * Elías Gabriel Pérez Uribe
  * Sergio Ignacio Villegas Osores
  * Hugo Francisco Manuel Zamora Pardo
