# Taller 3: MLFlow y Predicción de Ventas de Manzanas

Este taller explora el uso de MLFlow para el seguimiento de experimentos de machine learning, utilizando un caso práctico de predicción de demanda de manzanas en supermercados. Se generan datos sintéticos, se entrena un modelo de regresión y se registran los resultados y el modelo usando MLFlow.

## Requisitos
- Python 3.10 o superior
- [uv](https://github.com/astral-sh/uv) como manejador de paquetes

## Instalación
1. Instala uv si no lo tienes:
   ```powershell
   pip install uv
   ```
2. Instala las dependencias del proyecto:
   ```powershell
   uv pip install -r requirements.txt
   ```
   O para instalar y resolver dependencias desde el archivo pyproject.toml:
   ```powershell
   uv pip install .
   ```

## Uso
1. Inicia el servidor de MLFlow (opcional, si quieres ver la UI):
   ```powershell
   mlflow ui
   ```
2. Abre el notebook `Taller3.ipynb` y sigue las instrucciones paso a paso.

## Notas
- El taller incluye generación de datos sintéticos, entrenamiento de modelos y registro de experimentos en MLFlow.
- Puedes consultar la documentación oficial de MLFlow para más detalles: https://mlflow.org/docs/latest/index.html
