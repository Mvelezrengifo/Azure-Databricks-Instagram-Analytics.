📊 Instagram Analytics con Azure Databricks
Proyecto de Ingeniería de Datos que implementa una arquitectura Medallion (Bronce → Plata → Oro) en Azure Databricks, procesando más de 1.5 millones de registros sobre el uso de Instagram.

🏗️ Arquitectura de Datos (Medallion)
🥉 Bronce (Raw) → ingesta de datos brutos desde archivos CSV.

🥈 Plata (Silver) → limpieza, manejo de nulos y estandarización de tipos.

🥇 Oro (Gold) → agregaciones estratégicas para métricas de negocio:

Uso promedio por género.

Localización geográfica.

Nivel de satisfacción de usuarios.

🛡️ Gobernanza y Seguridad
Implementación de Data Governance mediante Views.

Los analistas acceden a resultados finales sin exponer lógica interna ni datos sensibles.

Principio de mínimo privilegio aplicado en accesos.

🛠️ Tecnologías Utilizadas
Azure Databricks

PySpark / Spark SQL

Delta Lake

Git & GitHub

📊 Resultados
Procesamiento distribuido de 1.5M registros.

Métricas de negocio listas para análisis en capa Oro.

Arquitectura reproducible y portable a entornos enterprise.

👤 Autor
Mauricio Vélez Rengifo  
Ingeniero de Datos | Desarrollador Backend

GitHub: Mvelezrengifo

LinkedIn: Mauricio Vélez
