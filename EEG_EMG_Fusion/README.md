# 🧠+💪 EEG_EMG_Fusion — Fusión multimodal para reconocimiento de gestos

Proyecto de **integración EEG + EMG**: resampling para alinear frecuencias, filtrado, extracción de potencia por bandas (EEG), características en tiempo (EMG), **PCA** y benchmarking de modelos.

## 🎯 Objetivo
Mejorar el reconocimiento de gestos combinando información de **actividad cerebral (EEG)** y **muscular (EMG)**.

## 🧩 Pipeline
1. **Resampling** para alinear frecuencias (p. ej., 250→200 Hz).
2. **Filtrado**: EEG (1–50 Hz) y EMG (10–100 Hz).
3. **Features**:  
   - EEG: potencia en bandas **delta, theta, alfa, beta, gamma**.  
   - EMG: **MAV, RMS, WL, STD**.  
4. **Normalización (Z-score)** y **PCA** (opcional).
5. **Modelos**: SVM · Random Forest · MLP.

## 🧠 Resultados (resumen)
- **Random Forest** ≈ **83%** de precisión (mejor balance entre rendimiento y tiempo).
- **MLP** similar en accuracy pero con mayor tiempo de predicción.
- **SVM** rápido pero menor desempeño global.

## 🧰 Librerías
`pandas`, `numpy`, `scikit-learn`, `matplotlib`

## 📁 Contenido
├── EEG_EMG.ipynb
└── LAB5_EMG_EEG.pdf # Guía/lab académico (referencia)
