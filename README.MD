# Telecom X – Análisis de Evasión de Clientes

## Descripción
Proyecto de análisis de datos enfocado en identificar factores asociados a la
evasión de clientes (Churn) en la empresa Telecom X.

## 🧪 Fuente de datos
Los datos se obtienen directamente desde una API en formato JSON:

- **Repositorio y API:**  
  https://github.com/ingridcristh/challenge2-data-science-LATAM  
- **Archivo JSON:**  
  `TelecomX_Data.json`

El dataset contiene información demográfica de los clientes, servicios contratados, métodos de pago y el estado de evasión (`Churn`).

## Tecnologías
- Python
- Pandas
- Matplotlib

### Instalación de dependencias
```bash
pip install pandas numpy matplotlib seaborn

## Estructura
- Notebook con proceso ETL
- Análisis exploratorio de datos
- Informe final con conclusiones

## Ejecución
Abrir el archivo `.ipynb` y ejecutar las celdas en orden.

## Metodología
El análisis sigue las siguientes etapas:

1. Extracción
Carga de datos desde la API en formato JSON.
Conversión a un DataFrame de pandas.

2. Transformación
Expansión de columnas anidadas.
Verificación de valores nulos y duplicados.
Revisión y corrección de tipos de datos.

3. Análisis
Análisis descriptivo del dataset.
Distribución de la variable Churn.
Análisis de evasión por variables categóricas y numéricas.
Visualización de patrones relevantes.

## Resultados
La evasión de clientes se concentra principalmente en contratos de tipo mensual.
Los clientes con menor tiempo de permanencia presentan mayor probabilidad de cancelar el servicio.
Existen diferencias claras en la evasión según el tipo de contrato y método de pago.

## Conclusiones y recomendaciones
Incentivar contratos de mayor duración puede reducir la evasión.
Implementar estrategias de retención en los primeros meses del cliente.
Analizar beneficios personalizados para clientes con alto riesgo de churn.

## Autora: Gretel Ariadne Beltran Peñaflor
