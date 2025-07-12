# Project-Analyzing-Students-Mental-Health
Análisis de cómo la longitud de la estancia afecta los puntajes de salud mental en estudiantes internacionales (SQL, DataCamp).


Este proyecto analiza la relación entre la **longitud de la estancia** y los **puntajes diagnósticos de salud mental** de los estudiantes internacionales, basándose en datos de una encuesta realizada como parte de un estudio.

## 📊 Descripción

El objetivo de este análisis fue explorar cómo el tiempo que un estudiante internacional ha pasado en el país anfitrión (`stay`) se correlaciona con sus puntajes en salud mental, medidos a través de tres pruebas diagnósticas:
- **PHQ-9** (`todep`): tamizaje de depresión
- **SCS** (`tosc`): escala de autocompasión
- **ASISS** (`toas`): estrés aculturativo

Para cada valor único de `stay` se calcularon:
- La cantidad de estudiantes internacionales
- El puntaje promedio en PHQ-9
- El puntaje promedio en SCS
- El puntaje promedio en ASISS

Todos los promedios están redondeados a dos decimales.

El análisis se realizó en SQL y agrupa los datos por `stay`, ordenando los resultados de mayor a menor `stay`.

## 📂 Archivos

- `mental_health_international_students.ipynb` — Jupyter Notebook con las consultas SQL y el análisis.
- `README.md` — Este archivo.

## 🔷 Herramientas Utilizadas

- SQL (GROUP BY, AVG, COUNT, ROUND)
- DataCamp DataLab (para escribir y probar consultas)
- GitHub (para alojar y compartir el proyecto)

## 🌱 Motivación

Este ejercicio fue realizado como parte de un proyecto práctico en DataCamp para fortalecer mis habilidades en SQL, especialmente en la agregación, agrupación y análisis de datos en escenarios similares a los del mundo real.
