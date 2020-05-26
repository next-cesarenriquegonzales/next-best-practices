# Título de la PoC

> PoC Snowflake

## Información General
> Se ha generado una PoC con la herramienta de datawarehouse SaaS Snowflake, donde se ha trabajado en los siguientes aspectos:
    • ¿Qué es Snowflake?
    • Arquitectura de Snowflake
    • Principales características de Snowflake
    • Casos de uso de Snowflake
    • Comparativa con otras herramientas del mercado
    • Generación de casos de uso batch y streaming en la nube de Azure


#### [v1.0]
> v1.0

#### Autores
> 
* Pedro Pablo Vaquero Jimenez (pedropablo.vaquero.next@bbva.com)
* Jorge Paredes Martínez de Velasco (j.paredes.mvelasco.next@bbva.com)


#### TRIBU1 TRIBU2 DD-MM-YYYY
> Azure Data Engineer 16-01-2020


#### keyword1, keyword2, keyword3
> Azure, Snowflake, datawarehouse, batch, streaming

## Introducción
> Snowflake es una herramienta de DWH diseñada para la nube que está teniendo una gran adopción en el mercado por parte de las empresas debido a su arquitectura patentada. ¿En qué consiste? ¿Qué aporta respecto a otros grandes competidores del mercado más consolidados? ¿En qué casos de uso aplica? ¿Cómo encaja dentro de una arquitectura de datos?

### Objetivo
> La presente PoC tiene varios objetivos:
    • Conocer Snowflake, su arquitectura y sus características principales.
    • Analizar su integración con diferentes herramientas de gestión del ciclo de vida del dato en la plataforma Azure.
    • Hacer una comparativa a nivel conceptal con otras herramientas competidoras del mercado.
    • Implementar algunos casos de uso utilizando Snowflake para ver cómo se utiliza y qué funcionalidades proporciona a una arquitectura Big Data en la nube. 

### Estado del arte
> Snowflake compite por el mercado DWH con herramientas como Amazon Redshift y Google BigQuery. A continuación añadimos un enlace a un documento generado donde se pueden visualizar diferentes tipos de estadísticas comparativas como por ejemplo: tipo de producto, comunidad, Cloud/On-premise y otras muchas características de las tres. 

	https://docs.google.com/document/d/1Ew72EQ8PkSBtvGC3o5spEeY2hklVKzHNMbcSKLSWzT0/edit#


### Resultados
> La primera tarea que se ha realizado ha sido una identificación de las funcionalidades más relevantes de Snowflake. Se ha hecho un descubrimiento del producto para poder entender sus capacidades.
Dada la extensión de la documentación generada ésta ha sido recogida en un documento aparte que se puede encontrar en:

	https://docs.google.com/document/d/1Ew72EQ8PkSBtvGC3o5spEeY2hklVKzHNMbcSKLSWzT0/edit

La implementación de los casos de uso de la PoC ha implicado configuración de numerosos componentes en Azure asi com la implementación de varias piezas código en función del caso de uso. Debido a la extensión se ha recogido en un documento aparte una Guía paso a paso en la que se describen los pasos a seguir para reproducir los casos de uso implementados. Dicha información se puede encontrar en:

	https://docs.google.com/document/d/1d-j8cJZ3p8gzkNUvauCj4j8ffLyX1uPiYEAv3EpiD7w/edit


# Bibliografía
> 
* Documentación oficial de snowflake, 2020. https://docs.snowflake.net/manuals/index.html
* Documentación oficial de AWS Redshift, 2020. https://docs.aws.amazon.com/redshift/index.html
* FAQ Redshift, 2019. https://aws.amazon.com/redshift/faqs/
* Snowflake Vs Redshift Comparison, 2019. Choosing the Right Data Warehouse: https://hevodata.com/blog/snowflake-vs-redshift/
* Snowflake’s Cloud Data Warehouse — What I Learned and Why I’m Rethinking the Data Warehouse, 2019. https://medium.com/hashmapinc/snowflakes-cloud-data-warehouse-what-i-learned-and-why-i-m-rethinking-the-data-warehouse-75a5daad271c
* Snowflake vs Amazon Redshift vs Google BigQuery, 2019. https://medium.com/@richiebachala/snowflake-redshift-bigquery-b84d2cb60168
* Test connectivity to Azure event hubs without writing any code, 2019. https://dev.to/azure/how-to-quickly-test-connectivity-to-your-azure-event-hubs-for-kafka-cluster-without-writing-any-code-4la1
