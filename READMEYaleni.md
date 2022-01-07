# WALMART
Desafio Walmart
Ingeniero de datos - Desafío
Este es el desafío básico para los ingenieros de datos.

Lider.cl quiere crear una nueva sección brillante para videojuegos, para llevar información personalizada de videojuegos a nuestros clientes, nuestro equipo de Analytics necesita un nuevo informe cada día con información de varios videojuegos. Esta información se utilizará para crear muchos modelos de aprendizaje automático y ciencia de datos para brindarles a nuestros clientes la mejor experiencia y tomar la mejor decisión sobre qué videojuego comprar.

Para este desafío, queremos que haga un trabajo que nos proporcione los datos para el equipo de análisis, pero con algunas inquietudes:

El trabajo debe ser un código ETL en Java, Scala o Python.
Necesitamos el modelo de datos para el problema.
Y queremos una implementación para este código.
Trabajo ETL
El trabajo debe recibir los conjuntos de datos y trae algunas cosas:

Los 10 mejores juegos para cada consola / empresa.
Los 10 peores juegos para cada consola / empresa.
Los 10 mejores juegos para todas las consolas.
Los 10 peores juegos para todas las consolas. Los datos están en la carpeta datos / en la raíz. El informe puede exponerse de la forma que desee, pero recuerde que se trata de un trabajo ETL.

 .- Se trabaja con Python en Google Collab, se deben implementar las librerias que se encuentran al inicio del cuaderno
Limpieza de archivos
Se analiza el archivo result.csv
* Se revisan si existen valores nulo, tipo de datos
* Se modifica el campo fecha
* Se crean dos campos nuevos como PERIODO_ANUAL Y PERIODO:MENSUAL
* Se normaliza el archivo, se realizan las consultas requerida
* Se exporta el archivo en formato xlsx
