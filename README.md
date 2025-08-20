# Análisis de Churn de Clientes – Telecom X

Este repositorio contiene el proyecto de análisis de **churn de clientes** para **Telecom X**, desarrollado como parte del desafío de Data Science LATAM. El objetivo principal es identificar los factores que contribuyen a la pérdida de clientes y proporcionar información que permita desarrollar estrategias de retención efectivas y modelos predictivos de churn.

---

---

## Extracción de Datos

Los datos de Telecom X se obtienen a través de la API definida en el repositorio oficial de referencia:

[Diccionario de Datos – Telecom X](https://github.com/ingridcristh/challenge2-data-science-LATAM/blob/main/TelecomX_diccionario.md)

Se utilizan las siguientes bibliotecas principales para la extracción y análisis de datos:

- `requests` – Para interactuar con la API y descargar los datos.  
- `pandas` – Para manipulación y limpieza de datos.  
- `numpy` – Para cálculos numéricos y análisis estadístico.  
- `matplotlib` y `seaborn` – Para visualización de datos.  

---

## Análisis Realizado

Se realizaron los siguientes pasos de análisis:

1. **Recopilación de datos** desde la API y verificación de calidad.  
2. **Limpieza y procesamiento** de los datos, incluyendo manejo de valores nulos y categorización de variables.  
3. **Análisis exploratorio de datos (EDA)** para identificar patrones y tendencias.  
4. **Visualización de métricas clave**, como:
   - Tasa de churn por meses de servicio.  
   - Perfil demográfico de los clientes que se van.  
   - Rango de cargos mensuales y tipo de contrato asociado al churn.  

### Hallazgos Clave

- La mayoría de los clientes que abandonan el servicio lo hacen dentro de los **primeros 24 meses**, con el **primer mes** mostrando la mayor tasa de cancelación.  
- Los clientes que se van suelen ser **menores de 65 años**.  
- Los cargos mensuales más asociados a churn están entre **60 y 100 dólares**.  
- La mayoría de los clientes que se van tienen **contratos mes a mes**.  

---

## Conclusiones y Recomendaciones

1. Implementar estrategias de **retención temprana**, especialmente en el primer mes de servicio.  
2. Incentivar contratos de mayor duración para clientes con contratos mes a mes.  
3. Monitorear rangos de cargos y ajustar precios o beneficios según el comportamiento de churn.  
4. Desarrollar modelos predictivos de churn basados en las características identificadas en este análisis.  

---

## Tecnologías Utilizadas

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab 

---
