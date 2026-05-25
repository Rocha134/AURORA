# AURORA

**AURORA: Analisis Unificado de Riesgo Operativo y Readiness con Aprendizaje Automatico**

Repositorio academico para las entregas semanales del proyecto de inteligencia artificial aplicada.

## Concepto del proyecto

AURORA es un caso de estudio academico sobre el uso de aprendizaje automatico para analizar senales genericas de calidad, riesgo y preparacion de liberaciones en flujos empresariales de software.

El proyecto busca estimar, con datos sinteticos, que cambios podrian requerir mayor validacion antes de avanzar dentro de un proceso de entrega. La idea central es explorar si metadatos no sensibles, como tamano del cambio, historial sintetico de fallas, evidencia disponible, cobertura simulada y complejidad de validacion, pueden apoyar decisiones mas trazables y basadas en evidencia.

AURORA no representa un producto comercial ni expone informacion interna. Es una version academica, sanitizada y autocontenida del problema de analisis.

## Aviso de privacidad

Este repositorio esta preparado para revision academica. Los datos incluidos son ficticios y fueron generados de forma sintetica para demostrar metodologia de analisis, preprocesamiento y modelado.

Por confidencialidad, el repositorio no incluye datos reales de Oracle ni informacion interna como repositorios, URLs, arquitectura, tecnologias propietarias, clientes, credenciales, procedimientos operativos, metricas reales o nombres de sistemas.

## Estructura

```text
.
├── entregas/
│   ├── avance_1_eda/
│   │   ├── Avance1.4.ipynb
│   │   ├── README.md
│   │   └── data/
│   │       └── release_readiness_synthetic.csv
│   ├── avance_2_feature_engineering/
│   │   ├── Avance2.4.ipynb
│   │   ├── README.md
│   │   └── data/
│   │       ├── aurora_features_model_ready.csv
│   │       └── aurora_feature_engineering_summary.csv
│   └── avance_3_baseline/
│       ├── Avance3.4.ipynb
│       ├── README.md
│       └── data/
│           ├── aurora_baseline_feature_importance.csv
│           ├── aurora_baseline_metrics.csv
│           ├── aurora_baseline_predictions.csv
│           └── figures/
├── requirements.txt
└── .gitignore
```

## Entregas disponibles

| Avance | Tema | Archivo principal | Estado |
|---|---|---|---|
| 1 | Analisis exploratorio de datos | `entregas/avance_1_eda/Avance1.4.ipynb` | Listo |
| 2 | Ingenieria de caracteristicas | `entregas/avance_2_feature_engineering/Avance2.4.ipynb` | Listo |
| 3 | Baseline | `entregas/avance_3_baseline/Avance3.4.ipynb` | Listo |

## Ejecucion

1. Crear un ambiente de Python.
2. Instalar dependencias con `pip install -r requirements.txt`.
3. Abrir la libreta del avance correspondiente.
4. Ejecutar todas las celdas de principio a fin.

## Nota metodologica

El caso de estudio representa senales genericas de calidad, validacion, riesgo operativo y preparacion de liberaciones en flujos empresariales de software. Las variables estan abstraidas para preservar privacidad y permitir una evaluacion academica segura.
