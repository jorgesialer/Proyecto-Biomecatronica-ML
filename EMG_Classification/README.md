
---

## 1.a) Proyecto: **EMG_Classification**  
**Archivo:** `EMG_Classification/README.md`

```markdown
# 💪 EMG_Classification — Reconocimiento de patrones en señales EMG

Proyecto de clasificación de movimientos a partir de **señales de Electromiografía (EMG)**. Incluye **limpieza**, **extracción de características** (tiempo) y **entrenamiento** de modelos clásicos de ML.

## 🎯 Objetivo
Predecir el gesto/movimiento a partir de ventanas de señal EMG utilizando características **MAV**, **RMS**, **Waveform Length (WL)** y **Desvío estándar**.

## 🧩 Pipeline
1. Carga de datos y EDA.
2. Limpieza y **normalización (Z-score)**.
3. Extracción de características por canal (ventaneo).
4. Entrenamiento y evaluación de **SVM**, **Random Forest** y **MLP**.

## 🧠 Métricas (resumen)
- **Mejor modelo:** **MLP**
- **F1-Score:** ≈ **0.71** (test), **0.55** (validación)
- Observación: clase 1 menos representada afectó el desempeño; SVM equilibró ciertas clases pero tuvo peor rendimiento global.

## 🧰 Librerías
`pandas`, `numpy`, `scikit-learn`, `matplotlib`

## 📁 Contenido
