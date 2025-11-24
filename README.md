Evolución del Sector Teatral en España (2016–2023)
Análisis del teatro en España + EDA específico del teatro musical
Dataset principal + Dataset musical + Datos complementarios
🟦 1. Introducción

Este proyecto analiza la evolución del sector teatral en España entre 2016 y 2023, incluyendo:

Volumen anual de espectadores

Ingresos generados por el teatro

Número de obras estrenadas

Impacto de la pandemia en el sector

Recuperación y tendencias recientes

Además, incorpora un análisis específico del teatro musical, uno de los motores económicos y culturales más relevantes dentro del teatro español.

El proyecto combina datos oficiales del Ministerio de Cultura, datos recopilados manualmente sobre la industria del musical y varios datasets complementarios para contextualizar el comportamiento del público y la inversión cultural en España.

🟩 2. Estructura del repositorio
/data_principal/
    teatro_espana_2016_2023_limpio.csv
    Eda_teatro_espana.ipynb

/data_musicales/
    musicales_limpio_final.csv
    Eda_data_musicales_PORTFOLIO.ipynb

/data_contexto/
    Asistencia_artes_escenicas2025.csv
    porcentaje_PIB_cultura_2023.csv
    precios_musicales_limpio.csv

README.md

🟥 3. Objetivos del proyecto
✔ Analizar la evolución del teatro en España:

Espectadores por año

Recaudación total

Número de musicales/obras estrenadas

✔ Identificar tendencias clave:

Caída por pandemia en 2021

Recuperación acelerada en 2022–2023

Ciclos de producción y consumo

✔ Estudiar el teatro musical como subindustria:

Volumen de producciones

Principales productoras

Teatros con mayor actividad

Comparación por años

✔ Integrar datos contextuales:

Inversión cultural (% del PIB)

Perfil demográfico de la asistencia

Precios del musical en 2026 (muestra manual real)

🟨 4. Contenido del análisis (resumen)
📌 EDA 1 – Teatro en España (2016–2023)

Incluye:

Limpieza y normalización de datos

Gráficas de evolución anual

Comparativa entre espectadores e ingresos

Detección de anomalías (impacto 2021)

Conclusiones económicas y culturales

Guarda el CSV final limpio

📌 EDA 2 – Teatro musical en España

Incluye:

Limpieza del dataset musical

Distribución por productora

Distribución por teatro

Giras sí/no

Evolución por año

Heatmaps y comparativas

Conclusiones específicas del segmento musical

📌 Datasets complementarios

No forman parte del EDA principal, pero enriquecen el proyecto:

Asistencia por sexo y edad

% del PIB destinado a cultura

Precios de musicales en 2026

🟦 5. Principales conclusiones
🟧 Teatro en España:

Estabilidad pre-pandemia (2017–2019)

Colapso histórico en 2021 por restricciones

Fuerte recuperación en 2022 y 2023

Ingresos y espectadores evolucionan en paralelo

Aumento significativo de obras estrenadas en los últimos años

🟩 Teatro musical:

Concentrado en Stage, SOM, LETSGO y Beon

Actividad centrada en Madrid (Coliseum, Lope de Vega, Rialto…)

Aumento notable de producciones desde 2021

La gira se consolida como estrategia clave

El musical actúa como motor económico del teatro español

🟦 Contexto:

La Administración Local es la que mayor % del PIB destina a cultura

Los jóvenes (15–34) tenían antes de la pandemia la mayor asistencia

Los precios del musical varían enormemente según producción y teatro

🟫 6. Tecnologías utilizadas

Python

Pandas

Matplotlib / Seaborn

Jupyter Notebook

CSV / UTF-8 / UTF-8-SIG

🟪 7. Próximas ampliaciones

EDA por Comunidad Autónoma (dataset listo pero pendiente de análisis)

Gráficas comparativas entre CCAA

Integración con Power BI / Tableau

Comparativa teatro vs. musical vs. artes escénicas globales

🟦 8. Autora

Proyecto realizado por Ela Ruiz González, artista y analista de datos especializada en el cruce entre artes escénicas y tecnología.
