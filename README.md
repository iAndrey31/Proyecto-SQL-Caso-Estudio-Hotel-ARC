# Análisis de Reservas Hoteleras con SQL

Proyecto final del curso **SQL for Data Analyst**, desarrollado como parte de mi especialización en Data Analyst en **Data Academy Latam**, con la orientación del profesor **Christian Condori**.

## Objetivo

Aplicar SQL al análisis de reservas hoteleras para explorar patrones de cancelación, canales de distribución y características de las reservas, conectando las consultas con preguntas de negocio.

## Herramientas utilizadas

- SQL en Databricks.
- Python, pandas y Spark para la carga inicial de datos.
- Tablas Delta.
- Databricks Workflows para una evidencia de ejecución de una consulta.

## Trabajo realizado

El proyecto incluye 20 ejercicios organizados en tres partes:

1. **Exploración y transformación:** filtros, agregaciones, clasificación con CASE WHEN, funciones de fecha y operaciones de modificación de datos.
2. **Análisis de negocio y cruces de tablas:** escenarios de costos asociados a cancelaciones y uso de LEFT, INNER, FULL OUTER y RIGHT JOIN.
3. **Análisis de cancelaciones:** comparación de tasas según presencia de hijos, solicitudes especiales, cambios en la reserva y tipo de hotel.

## Estructura del repositorio

- `Datos/`: archivo CSV utilizado en el caso de estudio.
- `QUERYS/01_CreacionTablas.ipynb`: carga inicial de datos y creación de tablas.
- `QUERYS/02_Parte1,2,3.ipynb`: desarrollo de los ejercicios y comentarios sobre los resultados.
- `QUERYS/03_Workflow_Evidencia.ipynb`: consulta independiente utilizada para la evidencia del workflow.
- `Job(Workflow) - Evidencias/`: captura del workflow.

## Aprendizajes

- Traducir preguntas de negocio en consultas SQL.
- Calcular indicadores y tasas de cancelación.
- Combinar información mediante distintos tipos de JOIN.
- Segmentar reservas e interpretar diferencias entre grupos.
- Documentar consultas y comunicar resultados.

## Alcance y consideraciones

Este es un proyecto académico. Los costos y algunas tablas auxiliares corresponden a supuestos o simulaciones de los ejercicios.

El ejercicio de ranking de países utiliza una tabla auxiliar de cuatro países, por lo que su resultado se limita a esos países.

Los análisis son descriptivos: las asociaciones observadas no demuestran causalidad.

Los notebooks conservan la secuencia de trabajo del curso. Algunas celdas modifican tablas o insertan registros; su ejecución repetida requiere revisar el estado previo de los datos.
