# transporte-santiago-sentiment-lstm

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![License: MIT](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

> ⚠️ **Disclaimer educativo**: Este dataset fue provisto por el curso [Nombre del Curso/Profesor] con fines académicos.
> Los datos son anonimizados y se usan solo para demostración de técnicas de ML/NLP.
> No representan datos de producción ni deben usarse comercialmente.

---

Análisis de sentimiento con LSTM para reseñas del transporte público de Santiago.

**Accuracy: 98%** | Dataset: 1,002 reseñas | 3 clases (Positivo, Neutro, Negativo)

## 🚀 Ejecución

```bash
pip install -r requirements.txt
python 06_nlp_preparation.py
python 07_model_training.py
```

## 📁 Estructura

```
06_nlp_preparation.py    # Tokenización, padding, encoding
07_model_training.py     # LSTM 2 capas, 825k parámetros
modelo_sentimiento_transporte.h5   # Modelo entrenado (7.77 MB)
tokenizer.pkl, label_encoder.pkl   # Para producción
X_train.npy, y_train.npy, etc.     # Datos de entrenamiento
confusion_matrix_dl.png            # Matriz de confusión
classification_report_dl.txt            # Metricas por clase
```

Ver ódigo completo en: https://github.com/TomasFuentealba/transporte-santiago-sentiment-lstm
