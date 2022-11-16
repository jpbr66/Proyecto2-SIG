# Proyecto2-SIG
Para este proyecto se tuvieron que realizar varias capas de datos *raster* y *vectoriales* y procesar estas

## Generación de mapas 
Para esta parte, después de agregar los datos necesarios, creamos una base de datos en Grass Gis y creamos
una localización que tendría las capas necesarias. Algunas capas agregadas son:
    
- geo_distritos

    Comando utilizado: `v.import input=geo_distritos.shp output=geo_distritos`

- geo_cantones

    Comando utilizado: `v.import input=geo_cantones.shp output=geo_cantones`

- geo_provincias

    Comando utilizado: `v.import input=geo_provincias.shp output=geo_provincias`
    
Cargamos todos estos para visualizar los datos, sin embargo solo hicimos uso de ***geo_cantones***


Posteriormente cargamos la capa de temblores con el siguiente comando:

    `v.import input=temblores.shp output=temblores`
