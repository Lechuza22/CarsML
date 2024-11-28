# CarsML
En este TP se clasificaron vehículos en "baratos" y "caros" usando la mediana de precios y un modelo de Árbol de Decisión, logrando 88% de exactitud. También se implementó un modelo de regresión, iniciando con Regresión Lineal (R²=0.90) y optimizando con Random Forest para predecir precios con alta precisión. 

# Resumen del Trabajo Realizado

En este proyecto, se abordaron los dos objetivos principales relacionados con el análisis de vehículos y sus precios en el mercado:

1. Clasificación de Vehículos en "Baratos" y "Caros"
Se utilizó la mediana de los precios como punto de corte para dividir los vehículos en dos categorías: "baratos" y "caros".
Se procesaron los datos:
Variables categóricas fueron codificadas.
Variables numéricas fueron normalizadas.
Se implementó un modelo de clasificación supervisado (Árbol de Decisión) para predecir la categoría de un vehículo.
Resultados:
Exactitud: 88%.
El modelo mostró un buen desempeño, especialmente al identificar vehículos caros (100% de sensibilidad).
Conclusión: El objetivo de clasificar correctamente los vehículos fue logrado con éxito.

2. Predicción del Precio Final de los Vehículos
Se implementó un modelo de regresión para predecir el precio exacto de un vehículo.
Se inició con un modelo de Regresión Lineal, que logró un R² de 0.90, explicando el 90% de la variabilidad de los precios.
Posteriormente, se optimizó un modelo de Random Forest:
Se usó búsqueda en rejilla para ajustar hiperparámetros.
El modelo mejorado redujo los errores y mostró un desempeño superior.
Resultados:
El modelo optimizado mostró un ajuste sólido, con métricas de error más bajas y una capacidad robusta para capturar la relación entre las características y el precio.

3. Conclusión General
Ambos objetivos fueron cumplidos:
- Clasificación: Los vehículos fueron categorizados correctamente en función de sus precios.
- Regresión: El modelo de predicción del precio final fue robusto y preciso.

El trabajo realizado proporciona insights clave para comprender y cotizar vehículos en el mercado, ayudando al cliente a tomar decisiones informadas y ajustadas a la demanda.
