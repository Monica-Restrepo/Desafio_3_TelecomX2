# Desafio_3_TelecomX2

Este proyecto desarrolla un sistema predictivo para identificar clientes con alta probabilidad de cancelar el servicio de internet, utilizando técnicas avanzadas de Machine Learning. El análisis incluye múltiples modelos predictivos y estrategias de retención basadas en datos.

Descripción del Dataset

Total de registros: 7,032 clientes
Variables: 42 características (transformadas a numéricas)
Variable objetivo: cancelo (0 = No canceló, 1 = Canceló)
Distribución: 73.4% no cancelan, 26.6% cancelan

Preprocesamiento

✅ Conversión de variables categóricas a numéricas (One-Hot Encoding)
✅ Sin valores faltantes
✅ Normalización para modelos que lo requieren
✅ División estratificada train/test (80/20)


Metodología
1. Análisis Exploratorio de Datos (EDA)

Análisis de correlaciones
Distribuciones por variable objetivo
Identificación de patrones y outliers
Matriz de correlación de variables top

2. Ingeniería de Características

Selección de 11 variables más relevantes basada en correlación
Eliminación de variables redundantes
Análisis de multicolinealidad

3. Modelado Predictivo

Implementación de 5 algoritmos diferentes
Optimización de hiperparámetros
Validación cruzada
Análisis de interpretabilidad por modelo

4. Evaluación y Comparación

Métricas múltiples: Precision, Recall, F1-Score, AUC
Análisis de matrices de confusión
Comparación de enfoques de balanceo de clases

Contacto
Autor: Monica Restrepo Cano
Email: monicarestrepo20@gmail.comm
LinkedIn: https://www.linkedin.com/in/monica-patricia-restrepo-cano-a78111a3/
Portafolio: https://github.com/Monica-Restrepo
