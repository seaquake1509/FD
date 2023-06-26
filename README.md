# Análisis de Financieros

## Resumen

El objetivo de este proyecto es aprovechar el poder del análisis de datos para mejorar la eficiencia operativa y respaldar la toma de decisiones estratégicas en la empresa "El Pato Azul". Mediante el análisis de conjuntos de datos internos financieros relevantes, se busca identificar patrones, tendencias y relaciones ocultas que puedan proporcionar información valiosa para mejorar la eficiencia, optimizar los procesos y brindar una ventaja competitiva.

## Objetivos del Proyecto

1. Recopilar, limpiar y estructurar los datos relevantes disponibles en la empresa, incluyendo fuentes internas y externas pertinentes.
2. Realizar un análisis exploratorio de los datos para identificar patrones, correlaciones y tendencias significativas.
3. Diseñar paneles interactivos y visualizaciones claras para presentar los resultados del análisis de manera comprensible y accesible para los diferentes equipos y niveles de la organización.
4. Realizar el estado de resultados financieros del 01 de enero al 31 de diciembre del 2020.
5. Proponer recomendaciones concretas basadas en los resultados del análisis para mejorar la eficiencia operativa, reducir costos, optimizar los recursos y respaldar la toma de decisiones estratégicas.

## Entregables Esperados

1. Un conjunto de datos limpios, estructurados y preparados para el análisis en Excel.
2. Informes y visualizaciones que presenten los hallazgos y recomendaciones de manera clara y concisa que respondan las siguientes preguntas:
   - El top 5 de costos de venta más elevados.
   - Top 10 de gastos operativos.
   - Los 5 meses en los que más se vendieron.
   - Los 2 meses en los que menos se vendieron.
3. Estado de resultados.
4. Recomendaciones concretas y accionables para mejorar la eficiencia operativa y respaldar la toma de decisiones.
5. Subir este análisis a su cuenta de GitHub.

## Recursos Necesarios

1. Excel.
2. Driver Snowflake.

## Recursos de Datos

1. JSON (Gastos de Venta).
2. SQL (Ventas).
3. Snowflake (Gastos Operativos).

## Procedimiento para elaborar el estado de resultados

El estado de resultados se elaborará siguiendo el siguiente cuadro:

| Concepto            | Fórmula                           |
|---------------------|-----------------------------------|
| Ventas              | SUM(VENTAS)                       |
| Costo de Ventas     | SUM(COSTO DE VENTAS)              |
| Utilidad Bruta      | Ventas - Costo de Ventas          |
| Gastos Operativos   | SUM(GASTOS OPERATIVOS)            |
| Utilidad Operacional | Utilidad Bruta - Gastos Operativos|
| ISR 1 Trimestre     | SUM(ENE, FEB, MAR) * 0.28         |
| ISR 2 Trimestre     | SUM(ENE, FEB, MAR) * 0.28         |
| ISR 3 Trimestre     | SUM(ENE, FEB, MAR) * 0.28         |
| ISR 4 Trimestre     | SUM(ENE, FEB, MAR) * 0.28         |
| Utilidad Neta       | Utilidad Operacional - ISR Tr
