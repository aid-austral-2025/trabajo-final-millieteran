# Trabajo Final

# TP Tsunami

Este proyecto analiza eventos sísmicos para explorar factores asociados a la ocurrencia de tsunamis.  
El trabajo está desarrollado en **QUARTO_AID** (.qmd), con visualizaciones de gráficos y un mapa.

## Contenido
- QUARTO_AID.qmd: documento principal con el análisis y código
- enunciado.md: consigna del trabajo práctico
- README.md: presentación del proyecto
- .Rproj: archivo de configuración del proyecto en RStudio


## Uso
Abrir "QUARTO_AID.qmd" en RStudio y renderizar el documento con Quarto.  
Se requieren los paquetes: "readr", "dplyr", "ggplot2", "leaflet", "sf","leaflet.extras".

---
El detalle metodológico y las conclusiones completas se encuentran en el informe principal.

Las variables que se observaron son las siguientes:

-   Magnitude: Magnitud del terremoto (escala Ritcher)

-   CDI: Intensidad percibida por la comunidad

-   MMI: Intensidad instrumental

-   SIG: Puntaje de significancia del evento

-   NST: Número de estaciones sísmicas que registraron el evento

-   DMIN: Distancia a la estación sísmica más cercana (en grados)

-   GAP: Brecha azimutal entre estaciones (en grados)

-   Depth: Profundidad focal del terremoto (en km)

-   Latitude: Latitud del epicentro (WGS84)

-   Longitude: Longitud del epicentro (WGS84)

-   Year: Año de ocurrencia del evento

-   Month: Mes de ocurrencia del evento

-   Tsunami: Presencia de tsunami