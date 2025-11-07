# 🧠 Biomecatrónica · Machine Learning aplicado a bioseñales (EMG & EEG)

Este repositorio reúne proyectos del curso **Fundamentos y Aplicaciones de Biomecatrónica (PUCP)** enfocados en el procesamiento de **señales EMG y EEG** y su uso en **modelos de Machine Learning** para reconocimiento de patrones.

## 📦 Proyectos incluidos
1. `EMG_Classification/` — Clasificación de movimientos a partir de **señales EMG** (extracción de características y ML).
2. `EEG_EMG_Fusion/` — **Fusión multimodal EEG+EMG** para reconocimiento de gestos (resampling, filtrado, PCA, benchmarking).

## 🧩 Objetivos de aprendizaje
- Limpieza y preprocesamiento de señales biomédicas.
- Extracción de características en **tiempo** (EMG) y **frecuencia** (EEG).
- Entrenamiento y evaluación de modelos (SVM, Random Forest, MLP).
- Integración de señales y **reducción de dimensionalidad** (PCA).

## 🧠 Resultados destacados (resumen)
- **EMG_Classification:** mejor F1-Score ≈ **0.71** (test) y **0.55** (validación) con **MLP**.
- **EEG_EMG_Fusion:** **Random Forest** alcanzó **≈83%** de precisión con tiempo de inferencia intermedio.

> Los detalles por proyecto están en los README de cada carpeta.
