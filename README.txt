Trabajo realizado por Erik Rivadeneira

*****************************Descripción de Proyecto****************************
El proyecto trata de una aplicación en React js que rastrea el número de infectados,
muertos y recuperados de COVID-19. Esta aplicación incluye los siguientes componentes:
* Tarjetas que muestran la información numérica de forma directa.
* Un selector que envía una solicitud para recuperar el número exacto de parámetros
  definidos anteriormente dependiendo del país seleccionado. 
* Un gráfico que cambia dependiendo de lo escogido en el selector.

Las APIs públicas utilizadas son las siguientes:
* Covid19 de mathdro>>>>>https://covid19.mathdro.id/api
* CovidTracking>>>>>https://api.covidtracking.com/v1/us/daily.json

Los tres componentes definidos anteriormente alimentan sus datos desde la API y
se incluye la funcionalidad interactiva en el cambio de datos y gráfico al cambiar
el valor del selector.
*************************Enlace del Video Tutorial*****************************
Para el desarrollo del proyecto se sigue el siguiente tutorial>>>>>>>>>>>>>>>>>
>>>https://www.youtube.com/watch?v=khJlrj3Y6Ls
Se añade dentro del componente Chart (gráfico) el siguiente import debido a un
error de CategoryScale con el Chart:import { Chart as ChartJS } from 'chart.js/auto'
*************************Enlace del Repositorio Git****************************
El proyecto se encuentra dentro del siguiente repositorio en Git>>>>>>>>>>>>>>>
>>>https://github.com/ErikRivadeneira/covtracker-rivadeneira-ingweb
**********************Enlace del Despliegue en Heroku**************************
El proyecto se puede ejecutar en este enlace>>>https://covtracker-rivadeneira-ingweb.herokuapp.com
Se utiliza este tutorial para desplegar el proyecto>>>https://www.youtube.com/watch?v=gItqzShex5M
En caso de que no cargue la aplicación, recargar la página web.

