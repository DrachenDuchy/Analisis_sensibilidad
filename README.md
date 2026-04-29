# Trabajo de grado: calidad del aire, salud pública y carga económica en Bogotá

Este repositorio contiene los insumos procesados, códigos, resultados, anexos y archivos de trazabilidad asociados al trabajo de grado:

**Un enfoque basado en principios de advección–difusión y modelos jerárquicos bayesianos para la evaluación de la sensibilidad en estimaciones de cargas sanitarias y económicas atribuibles a la calidad del aire en Bogotá.**

## Descripción general

El proyecto integra tres componentes principales:

1. Construcción de superficies espacio–temporales de concentración mediante un esquema tipo advección–difusión.
2. Estimación de superficies de exposición mediante modelos jerárquicos bayesianos espacio–temporales.
3. Evaluación sanitaria y económica inspirada en la lógica metodológica de BenMAP-CE, junto con análisis de sensibilidad.

## Estructura del repositorio

- `documento/`: versión final del documento y archivos LaTeX.
- `01_datos_procesados/`: bases de datos limpias y procesadas usadas en el análisis.
- `02_codigo/`: scripts y notebooks organizados por etapa metodológica.
- `03_resultados_figuras/`: figuras finales y complementarias.
- `04_resultados_tablas/`: tablas de resultados, métricas y sensibilidad.
- `05_anexos/`: material complementario para revisión.
- `06_logs_y_trazabilidad/`: inventarios, logs y archivos de trazabilidad.

## Nota sobre Sumapaz

Sumapaz fue incluida en todos los cálculos originales. Sin embargo, algunas figuras principales excluyen esta localidad únicamente con fines de visualización, debido a su peso espacial desproporcionado dentro de la malla de análisis. Los resultados completos con Sumapaz se conservan en las tablas, anexos y archivos de auditoría territorial.

## Reproducibilidad

Los scripts se encuentran organizados por etapa. Para reproducir el flujo completo, se recomienda seguir el orden de las carpetas dentro de `02_codigo/`.

## Autor

Juan Manuel Soto Morales  
Pontificia Universidad Javeriana  
Programa de Ciencia de Datos
