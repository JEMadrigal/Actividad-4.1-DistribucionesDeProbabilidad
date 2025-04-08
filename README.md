# Actividad-4.1-DistribucionesDeProbabilidad

# Análisis de Precios de Renta en Guadalajara

Este proyecto realiza un análisis de los precios de renta de inmuebles en Guadalajara utilizando `Fitter` para ajustar distribuciones a los datos.

## Requisitos

Instalar las siguientes bibliotecas:

```bash
pip install numpy==1.23.5 --force-reinstall
pip install pandas matplotlib fitter kagglehub --upgrade --force-reinstall
```

## Descripción

1. **Cargar el dataset**: Se descarga el conjunto de datos "robertrmz/guadalajara-rent-prices" usando `kagglehub`.
2. **Preprocesar datos**: Se filtra la columna `'price'` y se eliminan valores nulos.
3. **Visualización**: Se genera un histograma de los precios de renta.
4. **Ajuste de distribuciones**: Usando `Fitter`, se ajustan distribuciones como normal, exponencial, lognormal, gamma y beta.

## Ejecución

1. Instala las dependencias.
2. Ejecuta el script para obtener el histograma y los resultados del ajuste de distribuciones.
