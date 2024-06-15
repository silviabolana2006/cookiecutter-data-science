## Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial.

Politécnico Malvinas Argentinas.

Aprendizaje Automático

Autor: Bolaña Silvia


## Automatizacion de compra venta de bitcoin

Este proyecto tiene como objetivo desarrollar un sistema automatizado que tome decisiones de compra y venta de Bitcoin (BTC) basadas en datos históricos y patrones de comportamiento. A continuación, se presentan los aspectos clave del proyecto.


1_Preguntas Clave del Proyecto:

¿Es posible crear un modelo que siempre genere ganancias al operar con BTC?
¿Qué tipo de modelo de aprendizaje automático sería más adecuado para este propósito?
¿Los datos históricos pueden utilizarse para entrenar al modelo y establecer patrones de referencia?


2_Objetivo Principal:

Crear un modelo de aprendizaje automático que pueda operar de manera autónoma y generar ganancias al comprar y vender BTC.
Utilizar datos históricos para identificar patrones significativos en los precios del BTC,  con el objetivo de maximizar las ganancias.


3_Etapas del Proyecto:


   * Recolección de Datos y ETL:
Extraer datos históricos del comportamiento del BTC durante los últimos ocho años.
Procesar y clasificar los datos por día, semana y mes para reducir la cantidad de información.
   * Entrenamiento del Modelo:
Entrenar el modelo para reconocer patrones de subida del precio del BTC.
Utilizar el modelo para tomar decisiones de compra o venta en función de los datos actuales.
   * Visualización de Resultados:
Presentar los resultados utilizando gráficos y visualizaciones.
Evaluar la efectividad del sistema y comunicar los hallazgos.
                        
                               
## Herramientas utilizadas
    
 * Librerías pandas, numpy, matplotlib, Scikit-learn
 
 * Repositorio github, git        
 
 * Lenguaje python     
 
 * power bi, excel para ETL        



## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for {{ cookiecutter.module_name }}
│                         and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── {{ cookiecutter.module_name }}                <- Source code for use in this project.
    │
    ├── __init__.py    <- Makes {{ cookiecutter.module_name }} a Python module
    │
    ├── data           <- Scripts to download or generate data
    │   └── make_dataset.py
    │
    ├── features       <- Scripts to turn raw data into features for modeling
    │   └── build_features.py
    │
    ├── models         <- Scripts to train models and then use trained models to make
    │   │                 predictions
    │   ├── predict_model.py
    │   └── train_model.py
    │
    └── visualization  <- Scripts to create exploratory and results oriented visualizations
        └── visualize.py
```

--------

