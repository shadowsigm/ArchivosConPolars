﻿# Tutorial básico de Polars
## Fase 1 - Funciones básicas para el reemplazo de Pandas

> Este tutorial es parte de una serie de fases para el reemplazo de la librería Pandas en el ambiente de producción del empleador, cuyo nombre se mantendrá en reserva.

El procesamiento de datos que provienen desde los distintos equipos que se mueven en faenas mineras chilenas está siendo soportado por distintas librerías en Python por un área encargada de transformar y procesar los datos.

El área encargada de los datos ha sufrido una actualización, pasando de un punto nacional a uno regional, es decir, todo Latinoamérica. Actualmente, la infraestructura soporta bien el costo computacional, pero cuando comience a llegar el flujo de todos los datos de la región este colapsará sin remedio.

Se han realizado varias pruebas con librerías que pueden manipular los archivos de datos provenientes de la región, dando como sobresaliente el desempeño de la librería Polars, mostrando mejoras en el tiempo hasta de un quinto del costo computacional en cuanto a memoria y tiempo, versus Pandas.

En el tutorial aprenderemos funciones básicas, pero que son vitales en cuanto a ahorro de tiempo contra la librería Pandas. Además, se incluirá la información de como instalar la librería por medio de pip. Estas funciones corresponden a las siguientes:
* Filtrar columnas
* Filtrar filas
* Filtrar y agrupar valores
* Utilizar alias para las columnas

Fuera de ello, se realizarán algunas comparaciones en lectura de datos y procesamiento en función del tiempo.

Además, se añade el archivo CSV con el que se realizaron las pruebas.
