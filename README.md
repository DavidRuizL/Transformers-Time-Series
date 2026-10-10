# Transformers: From Attention to Time Series Forecasting

Exposición · Módulo de Machine Learning · Maestría en Ciencias de Datos y Analítica

Camilo Solano · David Ruiz · Juan Otálvaro

## Contenido

| Archivo | Descripción |
|---|---|
| `Transformers-Time-Series.pdf` | Diapositivas de la exposición |
| `Self_Attention_Live.ipynb` | Ejercicio práctico interactivo sobre atención |

## Exposición

Recorre el mecanismo de atención y la arquitectura Transformer, su adaptación al pronóstico de series de tiempo con PatchTST y TFT, sus límites frente a modelos simples y la importancia de una evaluación rigurosa: validación walk-forward, baselines y prevención de leakage.

## Ejercicio práctico

DistilGPT2 continúa un párrafo token por token y muestra, en cada paso, a qué tokens atendió cada una de sus 12 cabezas de atención y qué tokens tienen más probabilidad de venir después. Incluye además un ejemplo opcional en NumPy que calcula la self-attention paso a paso.

Para usarlo, abre el notebook en Colab y ejecuta las celdas en orden. La primera celda instala las dependencias y el modelo corre en CPU.

## Referencias

- Vaswani et al. (2017). *Attention Is All You Need*. arXiv:1706.03762
- Nie et al. (2023). *A Time Series is Worth 64 Words* (PatchTST). arXiv:2211.14730
- Lim et al. (2021). *Temporal Fusion Transformers*. arXiv:1912.09363
- Zeng et al. (2023). *Are Transformers Effective for Time Series Forecasting?* arXiv:2205.13504
