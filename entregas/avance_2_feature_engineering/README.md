# Avance 2. Ingenieria de caracteristicas

## Proyecto

**AURORA: Analisis Unificado de Riesgo Operativo y Readiness con Aprendizaje Automatico**

AURORA es un caso de estudio academico que utiliza datos sinteticos para explorar senales genericas de riesgo y preparacion de liberaciones en flujos empresariales de software. En este avance se prepara el dataset para modelado mediante construccion, transformacion, codificacion, normalizacion, seleccion y extraccion de caracteristicas.

## Entregable

- Nombre del entregable: `Avance2.4`
- Modalidad: individual
- Equipo: 4
- Archivo principal: `Avance2.4.ipynb`

## Archivos

- `Avance2.4.ipynb`: libreta principal de ingenieria de caracteristicas.
- `data/aurora_features_model_ready.csv`: dataset final preparado para modelado.
- `data/aurora_feature_engineering_summary.csv`: resumen auditable de transformaciones y decisiones.

## Privacidad

El dataset es completamente sintetico. No contiene datos reales de Oracle ni informacion confidencial. Las variables son genericas y fueron creadas para demostrar el proceso de preparacion de datos sin exponer sistemas, tecnologias, clientes, procedimientos, repositorios, credenciales ni metricas reales.

## Contenido cubierto

La libreta cubre:

- construccion de nuevas caracteristicas significativas;
- tratamiento de faltantes y alta cardinalidad;
- codificacion one-hot de variables categoricas;
- transformaciones logaritmicas y escalamiento;
- seleccion por umbral de varianza, correlacion, ANOVA y chi-cuadrado;
- extraccion exploratoria con PCA;
- conclusiones de preparacion de datos en contexto CRISP-ML.

## Ejecucion

Ejecutar `Avance2.4.ipynb` de forma secuencial desde la primera celda. El dataset del Avance 1 debe permanecer disponible en `../avance_1_eda/data/`.
