# Azure-Databricks-Instagram-Analytics.
# 📊 Análisis de Datos de Instagram - Arquitectura Medallion

Este proyecto demuestra una implementación profesional de Ingeniería de Datos utilizando **Azure Databricks** para procesar y analizar un dataset de **1.5 millones de registros** sobre el uso de Instagram.

## 🏗️ Arquitectura de Datos (Medallion)
Implementamos una estructura de tres capas para garantizar la calidad y seguridad de los datos:

* **Capa Bronce (Raw):** Ingesta de datos brutos desde archivos CSV.
* **Capa Plata (Silver):** Limpieza de datos, manejo de nulos y estandarización de tipos.
* **Capa Oro (Gold):** Agregaciones estratégicas para métricas de negocio (Uso promedio por género, localización y nivel de satisfacción).

## 🛡️ Gobernanza y Seguridad
Se implementó una capa de **Gobernanza de Datos** mediante el uso de **Vistas (Views)**, permitiendo que los analistas accedan a los resultados finales sin exponer la lógica de procesamiento ni datos sensibles del backend.

## 🛠️ Tecnologías Utilizadas
* **Azure Databricks**
* **PySpark / Spark SQL**
* **Git & GitHub**
* **Delta Lake**
