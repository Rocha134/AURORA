# Avance 3. Baseline

## Proyecto

**AURORA: Analisis Unificado de Riesgo Operativo y Readiness con Aprendizaje Automatico**

AURORA es un caso de estudio academico que utiliza datos sinteticos para explorar senales genericas de riesgo y preparacion de liberaciones en flujos empresariales de software. En este avance se construye un modelo baseline para evaluar la viabilidad inicial del problema de clasificacion.

## Entregable

- Nombre del entregable: `Avance3.4`
- Modalidad: individual
- Equipo: 4
- Archivo principal: `Avance3.4.ipynb`

## Archivos

- `Avance3.4.ipynb`: libreta principal del modelo baseline.
- `data/aurora_baseline_metrics.csv`: metricas del dummy baseline y la regresion logistica.
- `data/aurora_baseline_feature_importance.csv`: importancia de caracteristicas por coeficientes y permutacion.
- `data/aurora_baseline_predictions.csv`: predicciones generadas por el baseline.
- `data/figures/`: graficas de matriz de confusion, curvas PR/ROC, curva de aprendizaje e importancia.

## Privacidad

El dataset es completamente sintetico. No contiene datos reales de Oracle ni informacion confidencial. Las variables son genericas y fueron creadas para demostrar el proceso de modelado baseline sin exponer sistemas, tecnologias, clientes, procedimientos, repositorios, credenciales ni metricas reales.

## Contenido cubierto

La libreta cubre:

- justificacion del algoritmo baseline;
- comparacion contra un modelo dummy;
- seleccion de metrica principal alineada al problema;
- evaluacion train/test;
- validacion cruzada;
- curva de aprendizaje para analizar sub/sobreajuste;
- matriz de confusion, curva PR y curva ROC;
- importancia de caracteristicas por coeficientes y permutacion;
- desempeno minimo esperado para modelos posteriores.

## Ejecucion

Ejecutar `Avance3.4.ipynb` de forma secuencial desde la primera celda. El dataset del Avance 2 debe permanecer disponible en `../avance_2_feature_engineering/data/`.
