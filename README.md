Repositorio del equipo Databuesos

Para reproducir los resultados de este repositorio es necesario contar con la distribución [Anaconda](https://www.anaconda.com/products/individual) de Python y también con el software [Stata](https://www.stata.com/) para ejecutar uno de los notebooks.

**Introducción**

En este repositorio analizo los datos del módulo de negocios no agrícolas de la Encuesta Nacional de Ingresos y Gastos de los Hogares (ENIGH, 2020) para explorar las formas de pago alternativas al efectivo que usan los micronegocios familiares en México y obtener un panorama sobre los retos que enfrentan para la adopción de nuevas formas de pago.

**Análisis**

* El documento de análisis se encuentra en [Formas de pago alternativas en micronegocios familiares.pdf](https://github.com/jjsantos01/datamexico_mipymes_2022/blob/master/Formas%20de%20pago%20alternativas%20en%20micronegocios%20familiares.pdf)
* El notebook [01_analisis_negocios_enigh.ipynb](https://github.com/jjsantos01/datamexico_mipymes_2022/blob/master/01_analisis_negocios_enigh.ipynb) contiene las principales estadísticas descripctivas (Esto es código de Python). 
* El notebook [02_estimacion_modelos.ipynb](https://github.com/jjsantos01/datamexico_mipymes_2022/blob/master/02_estimacion_modelos.ipynb) contiene las estimaciones del modelo logístico (OJO, esto es código de Stata, debe ejecutarse en Stata).
* El notebook [03_grafica_regresion.ipynb](https://github.com/jjsantos01/datamexico_mipymes_2022/blob/master/03_grafica_regresion.ipynb) genera la gráfica con los resultados de la regresión logística. 

**Fuentes de datos**:

* Censo económico: uso los datos del Censo Económico que provee la API de DataMéxico en el cubo indicators_economic_census para explorar la tenencia de cuentas por parte de las unidades económicas.
* Encuesta Nacional de Ingresos y Gastos, 2020, INEGI.: Catálogo de metadatos
