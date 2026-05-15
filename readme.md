# Práctica 2

En este proyecto estudiamos las diferencias entre los modelos XGBoost y LightGBM, tanto balanceados como no balanceados, para la predicción de impagos.

## Cómo ejecutar el proyecto
1. **Entorno**: Este proyecto se ha realizado por completo en VS Code con las extensiones de Python y Jupyter, para poder leer notebooks de Python
2. **Archivos pkl**: Debido a las limitaciones de espacio de GitHub, es necesario introducir los archivos 'filter.pkl' y 'preprocessor.pkl' en la misma carpeta que el notebook, y los datos dentro de 'data/filtered', para que funcione el código
3. **Librerías**: Es posible instalar todas las librerías utilizadas en el proyecto a través del siguiente comando en la terminal: 'pip install pandas numpy matplotlib scikit-learn lightgbm xgboost optuna optuna-integration'
4. **Ejecución**: Abrir el archivo 'practica2_notebook.ipynb' y ejecutar las celdas de código en orden

## Detalles técnicos destacados
1. **Métrica utilizada**: Log Loss
2. **Optimización**: Uso de Optuna con 'HyperbandPruner' para la optimización de hiperparámetros
3. **Reproducibilidad**: Semilla global en todo el proyecto 