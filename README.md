# Proyecto-Biomecatronica-ML
Proyectos desarrollados en el curso Fundamentos y Aplicaciones de Biomecatrónica (PUCP), enfocados en análisis y clasificación de señales biomédicas mediante ML.

# Machine Learning aplicado a señales biomédicas (EMG y EEG)

Este repositorio reúne proyectos desarrollados en el curso **Fundamentos y Aplicaciones de Biomecatrónica (PUCP)**, enfocados en el procesamiento de señales biológicas y el uso de **modelos de Machine Learning** para el reconocimiento de patrones musculares y cerebrales.

## 🧠 Contenido

### 1. EMG_Classification
- Procesamiento de señales de electromiografía (EMG)
- Extracción de características en el dominio del tiempo (MAV, RMS, WL, STD)
- Entrenamiento de modelos: Random Forest, SVM, MLP
- **Mejor modelo:** MLP (F1-Score 0.71 test / 0.55 validación)

### 2. EEG_EMG_Fusion
- Integración de señales EEG y EMG mediante resampling (200 Hz)
- Filtrado, normalización (Z-score) y reducción de dimensionalidad (PCA)
- Benchmarking de modelos: Random Forest, SVM, MLP
- **Mejor modelo:** Random Forest (83% de precisión)

## 🧰 Tecnologías utilizadas
- Python (Pandas, NumPy, Scikit-learn, Matplotlib)
- Procesamiento de señales (Filtrado, Normalización, PCA)
- Machine Learning (SVM, Random Forest, MLP)
- Métricas de rendimiento (F1-score, Accuracy, Precision)

## 📚 Créditos
Desarrollado por **Jorge Eduardo Sialer Kanamori**
