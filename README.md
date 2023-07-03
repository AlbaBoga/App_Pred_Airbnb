# Proyecto Airbnb Toronto

## Contenido

* [Enlace a la sección](https://github.com/AlbaBoga/DataAnalyticsPorfolio/tree/main/Project_AirbnbToronto)
* Programación en `Python`.
* Análisis de los datos pertenecientes a las ofertas de Airbnb Toronto, obtenido de la web [Inside Airbnb](http://insideairbnb.com/toronto)
* Preprocesamiento de los datos, buscando valores nulos, valores duplicados y limpieza de columnas pertinentes.
* Utilización de la librería `plotly y folium` para la visualización de los datos.
* Uso de la librería `pycaret` y el modelo de regresión `huber` para la creación de un predictor que permita estimar el precio de futuras ofertas.
* Uso de la herramienta `Power BI` para crear un panel que permita resumir los datos más importantes.
* Conclusiones de los datos.
* Utilización de la herramienta `Streamlit` para la visualización y explicación de los datos.
* [Enlace a la aplicación](https://airbnbtoronto.streamlit.app/)

## Predictor

* [Enlace al predictor de ofertas](https://predictorairbnb.streamlit.app/)
* Se utiliza la librería `pycaret` y los modelos de regresión para estimar cuál ofrece la mejor predicción del precio diario de las ofertas.
* Se utiliza el modelo de regresión `huber` y se implementa el modelo.
* Se utilizan como parámetros el tipo de habitación, el número de personas, el número de noches mínimas, la disponibilidad de la oferta con un año de antelación, el tipo de alquiler, si tiene licencia disponible, la zona y el barrio.
