# Gold Recovery Efficiency Prediction 🏭

## 📋 Descripción del Proyecto
Este proyecto simula un entorno industrial real para la empresa **Zyfra**. El objetivo es desarrollar un modelo predictivo que optimice la producción de oro, identificando parámetros ineficientes en las etapas de purificación. Se construyó un modelo de Machine Learning para predecir el coeficiente de recuperación de oro, minimizando el error en función de métricas de negocio.

## 🛠️ Tecnologías Clave
* **Python** (Pandas, NumPy, Scikit-learn).
* **Modelado:** Random Forest Regressor, Linear Regression.
* **Métrica Personalizada:** sMAPE (Symmetric Mean Absolute Percentage Error).
* **Validación:** Cross-Validation para series temporales.

## ⚙️ Metodología
1.  **Preprocesamiento:** Manejo de datos de sensores industriales y limpieza de outliers en series temporales.
2.  **Análisis Exploratorio (EDA):** Estudio de la evolución de la concentración de metales (Au, Ag, Pb) a través de las etapas de flotación y purificación.
3.  **Evaluación:** Implementación de la fórmula sMAPE requerida para penalizar errores de subestimación y sobreestimación por igual.
4.  **Optimización:** Ajuste de hiperparámetros para superar el baseline del modelo "Dummy".

## 📊 Resultados
* [cite_start]**Métrica Final:** Se alcanzó un **sMAPE de 9.36%** en el conjunto de prueba[cite: 22].
* El modelo de **Random Forest** demostró ser el más robusto para capturar la no-linealidad de los procesos químicos involucrados.

## 📁 Disponibilidad de los Datos
**Nota:** Los datasets utilizados en este proyecto son propiedad de TripleTen y se utilizan bajo licencia educativa. Debido a restricciones de derechos de autor y límites de tamaño, los archivos fuente `.csv` no se incluyen en este repositorio.
> 💡 **Cómo ver el proyecto:** Puedes visualizar todo el análisis, las gráficas y los resultados renderizados abriendo directamente los archivos `.ipynb` en este repositorio.
