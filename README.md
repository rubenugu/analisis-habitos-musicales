# Análisis de hábitos musicales: Springfield vs Shelbyville

## Descripción

Análisis exploratorio de más de 65,000 registros de reproducción musical
para determinar si los hábitos de escucha varían según la ciudad y el
día de la semana.

## Hallazgos clave

- Springfield registra 2.3x más reproducciones que Shelbyville,
  proporcional a su diferencia de población (~3:1).
- El día de la semana no genera diferencia significativa (2.2%
  entre lunes y viernes).

## Proceso

1. **Exploración:** Identificación de problemas en nombres de columnas,
   valores nulos y duplicados.
2. **Limpieza:** Normalización de columnas a snake_case, imputación de
   nulos, eliminación de 3,826 duplicados (5.9%) y corrección de
   duplicados implícitos en géneros.
3. **Análisis:** Comparación de volumen de reproducciones segmentado
   por ciudad y día de la semana.

## Tecnologías

- Python 3
- pandas

## Cómo ver el proyecto

Puedes ver el notebook directamente en GitHub o abrirlo en Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rubenugu/analisis-habitos-musicales/blob/main/analisis_habitos_musicales.ipynb)

## Estado

✅ Completado
