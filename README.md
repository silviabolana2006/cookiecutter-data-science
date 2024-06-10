Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial

Politécnico Malvinas Argentinas

Aprendizaje Automático



Autora: Silvia Bolaña




AUTOMATIZACION DE COMPRA VENTA DE BTC

Entrega 1: Descripción y Formulación del Objetivo:

COMPLETAR

Las preguntas de investigación del proyecto son:

COMPLETAR


Las distintas etapas del proyecto son:

Obtención de los datos: datos de los análisis de la presencia de toxinas en distintos moluscos, datos meteorológicos y oceanográficos de los mismos periodos.
Integración y limpieza de los datos provenientes de las distintas fuentes.
Análisis exploratorio de los datos en busca de comprender mejor los datos y encontrar patrones y preparación de los datos para el modelado.
Modelar los datos en los distintos algoritmos de clasificación que podemos utilizar y analizar sus resultados, en esta etapa también se optimizan los distintos modelos y culminan con la elección del modelo más eficiente.
Visualizar y comunicar los resultados del modelo.
Estas etapas si bien siguen un orden se retroalimentan y pueden retomarse o reiniciarse en base a las salidas de las otras etapas.


Organización del Repositorio:



├── LICENSE

├── Makefile           <- Makefile con comandos como `make data` o `make train`

├── README.md          <- El README del nivel superior para desarrolladores o usuarios de este proyecto.

├── data

│   ├── external       <- Datos de fuentes externas.

│   ├── interim        <- Datos intermedios que han sido transformados.

│   ├── processed      <- Datasets finales para el modelado.

│   └── raw            <- Datos crudos internos.

│
├── docs               <- Un proyecto Sphinx por defecto, vea sphinx-doc.org para mas detalles.

│
├── models             <- Modelos entrenados, predicciones o resumenes de modelos.

│
├── notebooks          <- Jupyter notebooks. La convencion para            		nombrarlos es un

│                                    numero (para ordenarlos) seguido de las iniciales del creador y una descripcion corta 

│                                   demilitada por "-" por ejemplo `1.0-jqp-exploracion-inicial-datos`.

│
├── references         <- Diccionario de datos, manuales y otro material explicativo.
│

├── reports            <- Analisis generado como HTML, PDF, LaTeX, etc.

│   └── figures        <- Graficos y figuras generadas para ser usadas en reportes.
│

├── requirements.txt   <- El archivo de requerimientos para reproducir el ambiente de analisis por ejemplo

│                         generado con `pip freeze > requirements.txt`

│
├── setup.py           <- hace el proyecto instalable mediante pip  (pip install -e .) asi src puede ser importado. can be imported

├── src                <- Codigo fuente usado en este proyecto.

│  ├── __init__.py    <- Hace a src un modulo de Python

│   │
│   ├── data           <- Scripts para descargar o generar los datos.


│   │   └── make_dataset.py
│   │

│   ├── features       <- Scripts para transformar los datos crudos en features para el modelado.

│   │   └── build_features.py
│   │

│   ├── models         <- Scripts para entrenar modelos y luego hacer predicciones.


│   │   ├── predict_model.py


│   │   └── train_model.py
│   │

│   └── visualization  <- Scripts para crear visualizaciones orientadas a la exploracion de datos o a los resultados.

│       └── visualize.py
│

└── tox.ini            <- archvi tox con ajustes para ejecutar tox; vea tox.readthedocs.io



  
 


Proyecto basado en la plantilla de proyecto de ciencia de datos cookiecutter . #cookiecutterdatascience
