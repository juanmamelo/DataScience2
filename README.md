
# 🏠📊 Análisis del Mercado Inmobiliario en Melbourne

Este repositorio contiene el proyecto final de la cursada **Data Science II** en Coderhouse. El objetivo principal es realizar un análisis profundo de los datos del mercado inmobiliario en Melbourne, Australia, para identificar tendencias, relaciones entre variables y construir modelos predictivos de precios de propiedades.

---

## 📌 Objetivos

- Realizar un análisis exploratorio completo del dataset de propiedades en Melbourne.
- Detectar patrones y correlaciones entre las variables.
- Entrenar modelos de regresión para predecir el precio de las viviendas.
- Evaluar métricas y visualizaciones para entender el rendimiento de los modelos.

---

## 🧱 Estructura del Proyecto

```
DataScience2/
├── data/                # Dataset original y archivos procesados
├── notebooks/           # Análisis completo en Jupyter Notebook
├── img/                 # Visualizaciones exportadas
├── README.md            # Este archivo
```

---

## 📊 Dataset

- Fuente: [Kaggle – Melbourne Housing Market](https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot)
- Variables principales: suburbio, número de habitaciones, tamaño del terreno, tipo de propiedad, precio, etc.
- Formato: CSV

---

## 📈 Técnicas utilizadas

- Análisis exploratorio de datos (EDA)
- Visualizaciones con `Seaborn`, `Matplotlib` y `Plotly`
- Correlaciones, outliers, tratamiento de nulos
- Regresión lineal, regresión de árbol de decisión, XGBoost
- Evaluación con RMSE, MAE y R²

---

## 📦 Librerías principales

- `pandas`, `numpy`
- `matplotlib`, `seaborn`, `plotly`
- `scikit-learn`
- `xgboost`

---

## 🧪 Ejemplo de predicción

```python
from sklearn.linear_model import LinearRegression
model = LinearRegression()
model.fit(X_train, y_train)
preds = model.predict(X_test)
print("R²:", model.score(X_test, y_test))
```

---

## 🧑‍💻 Autor

Juan Manuel Melo  
🔗 [LinkedIn](https://www.linkedin.com/in/juan-manuel-melo95/)  
📧 juanmanuelmelo95@gmail.com

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Ver el archivo `LICENSE` para más detalles.
