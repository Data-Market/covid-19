# Datasets de Catastro

<a href="https://datamarket.es">
  <img src="https://datamarket.es/media/banners/covid-19-banner.png">
</a>

## Descripción

Datos del Ministerio de Sanidad sobre __la evolución del virus COVID-19 en España.__ Los datos de la última semana están sujetos a revisión y no deberían tomarse en cuenta en los análisis, por tanto no se han publicado.

Las características de este dataset son las siguientes:

* __Frecuencia de actualización__: actualizado cada 24h
* __Volumen estimado__: 
* __Histórico__: 

El dataset completo se puede adquirir en [DataMarket](https://datamarket.es/#covid-19-dataset), plataforma de referencia de datos externos en España. 

Este repositorio contiene los siguientes recursos:

* La documentación completa del dataset.
* Una muestra representativa del mismo disponible para su evaluación y uso gratuito.

## Muestra

La muestra se encuentra disponible para descarga en el siguiente [link]().

## Documentación

A continuación se muestran las columnas de las que consta el dataset junto con su descripción.

| nombre | tipo | descripción | ejemplo |
|--------|------|-------------|---------|
| age_interval | str | Intervalo de años en el cual se ubica el grupo de análisis. | 70-79 |
| autonomous_region | str | Comunidad autónoma donde se registran los datos. | Comunidad de Madrid |
| date | datetime | Fecha del momento en el cual se obtuvieron los datos. | 2020-12-12 |
| num_dead | int | Número de muertes que se han producido en el grupo de análisis. | 1 |
| num_hosp | int | Número de hospitalizaciones que ha tenido el grupo de análisis. | 5 |
| num_infections | int | Número de infecciones que han se han reportado en el grupo de análisis. | 36 |
| num_uci | int | Número de ingresos en la Unidad de Cuidados Intensivos que ha tenido el grupo de análisis. | 0 |
| province | str | Provincia donde se registran los datos. | Madrid |
| sex | int | Sexo del grupo de análisis (H, M, NC). | M |
