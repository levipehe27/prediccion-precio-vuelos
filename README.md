# prediccion-precio-vuelos
Modelos de regresión lineal para predicción de precios de vuelos

##  Descripción

Este proyecto desarrolla modelos de regresión lineal para predecir el precio de vuelos a partir de variables como clase, duración, número de escalas, entre otras.

##  Objetivo

Evaluar qué variables explican mejor el precio de los vuelos y construir un modelo capaz de generalizar correctamente a nuevos datos.

##  Contenido del análisis

* Análisis exploratorio de datos (EDA)
* Preprocesamiento y manejo de variables categóricas
* Regresión lineal simple
* Regresión lineal múltiple
* Validación del modelo (train/test)
* Reducción de dimensionalidad (PCA)

## Resultados

El modelo de regresión multilineal mostró mejor desempeño:

| Métrica | Modelo Simple | Modelo Multilineal |
| ------- | ------------- | ------------------ |
| R²      | 0.8832        | 0.9137             |
| MAE     | 4876.46       | 4563.17            |
| RMSE    | 7794.63       | 6702.56            |

##  Conclusiones

* La combinación de variables mejora significativamente la predicción del precio.
* El modelo multilineal logra menor error y mayor capacidad explicativa.
* Técnicas como PCA no mejoraron significativamente el desempeño en este caso.

##  Tecnologías usadas

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

##  Cómo usar

1. Clonar el repositorio
2. Instalar dependencias:

   ```bash
   pip install -r requirements.txt
   ```
3. Ejecutar el notebook

---

📌 *Proyecto académico enfocado en análisis de datos y modelado predictivo.*
