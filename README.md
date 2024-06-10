Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial
Politécnico Malvinas Argentinas
Aprendizaje Automático

Autora: Silvia Bolaña

AUTOMATIZACION DE COMPRA VENTA DE BTC

Entrega 1: Descripción y Formulación del Objetivo:
*****
COMPLETAR

Las preguntas de investigación del proyecto son:
******
COMPLETAR


Las distintas etapas del proyecto son:

Obtención de los datos: datos de los análisis de la presencia de toxinas en distintos moluscos, datos meteorológicos y oceanográficos de los mismos periodos.
Integración y limpieza de los datos provenientes de las distintas fuentes.
Análisis exploratorio de los datos en busca de comprender mejor los datos y encontrar patrones y preparación de los datos para el modelado.
Modelar los datos en los distintos algoritmos de clasificación que podemos utilizar y analizar sus resultados, en esta etapa también se optimizan los distintos modelos y culminan con la elección del modelo más eficiente.
Visualizar y comunicar los resultados del modelo.
Estas etapas si bien siguen un orden se retroalimentan y pueden retomarse o reiniciarse en base a las salidas de las otras etapas.


Organización del Repositorio:


├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         {{ cookiecutter.module_name }} and configuration for tools like black
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
└── {{ cookiecutter.module_name }}   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes {{ cookiecutter.module_name }} a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations


Proyecto basado en la plantilla de proyecto de ciencia de datos cookiecutter . #cookiecutterdatascience
