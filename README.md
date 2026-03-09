# Movilidad urbana y productividad económica en ciudades de América Latina

## Descripción del proyecto

Este proyecto analiza la relación entre **la congestión del tráfico urbano** y **la productividad económica** en ciudades de América Latina.

El objetivo es identificar ciudades donde la **movilidad urbana puede estar afectando el desempeño económico**, con el fin de apoyar decisiones de inversión en **infraestructura de transporte**.

El análisis combina dos fuentes de datos reales:

* **TomTom Traffic Index**: indicadores de congestión y tráfico urbano.
* **OECD Cities Dataset**: indicadores económicos y demográficos de ciudades.

El resultado final es un **dataset integrado y limpio para el año 2024**, que permite analizar cómo la movilidad urbana se relaciona con el desarrollo económico.

---

# Preguntas del negocio

Este análisis busca responder las siguientes preguntas:

* ¿Qué ciudades de América Latina presentan **alta congestión y baja productividad económica**?
* ¿Qué ciudades muestran **mejor equilibrio entre movilidad eficiente y economía fuerte**?
* ¿Qué variables de movilidad parecen tener **mayor relación con el desarrollo urbano**?

---

# Fuentes de datos

## TomTom Traffic Index

Base de datos que contiene indicadores de tráfico en tiempo real para ciudades del mundo.

Variables relevantes utilizadas:

* Índice de tráfico (Traffic Index)
* Retraso total por congestión (Jams Delay)
* Longitud de embotellamientos
* Tiempo de viaje por cada 10 km
* Retraso promedio en minutos

## OECD Cities Dataset

Dataset de indicadores urbanos y económicos recopilados por la OECD.

Variables utilizadas:

* PIB per cápita de la ciudad
* Tasa de desempleo
* Población
* Contaminación del aire (PM2.5)

---

# Metodología

El proyecto sigue el siguiente flujo de trabajo:

1. Carga y exploración de los datasets
2. Limpieza y estandarización de variables
3. Extracción del año y filtrado del período **2024**
4. Agregación de indicadores de tráfico por ciudad
5. Integración de datasets de movilidad y economía
6. Análisis exploratorio de datos y visualización de relaciones
7. Generación de un dataset final listo para análisis

---

# Herramientas utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# Estructura del proyecto

```
notebooks/
    mobility_economy_analysis.ipynb

src/
    data_cleaning.py
```

---

# Resultados principales

El análisis exploratorio sugiere que las ciudades con **mayores niveles de congestión** tienden a presentar **menores niveles de productividad económica y mayores tasas de desempleo**.

Esto sugiere que mejorar la **infraestructura de transporte urbano** podría contribuir a aumentar la eficiencia económica y el bienestar urbano.

---

# Dataset final

El proyecto genera un dataset limpio y consolidado que incluye:

* Indicadores de congestión urbana
* Indicadores económicos
* Indicadores demográficos

Con **una fila por ciudad para el año 2024**, listo para análisis posteriores o visualizaciones.

---

# Autor

Alejandra P.

Proyecto de análisis de datos
Escenario académico: Latin American Development Bank
