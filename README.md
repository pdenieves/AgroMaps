# AgroMaps - Google Maps as a help for agriculture

El uso de mapas interactivos y por satélite son de gran ayuda en la administración y control de parcelas y en la gestión de explotaciones agrarias y forestales. 

Con este proyecto exploraré las diferentes posibilidades y retos técnicos para la visualización de cultivos y el tratamiento de datos geográficos. Para el mapa sobre el que trabajar será Google Maps. Iré subiendo a este repositorio las diferentes versiones y módulos de software, principalmente en **Python**.


Notas de la *primera versión*:
 - Sobre el mapa se visualizan las parcelas y puntos de interés.
 - Los colores de las parcelas corresponden el tipo de cultivo o al propietario, según el parámetro 'mode'.
 - Las coordenadas de las parcelas se extraen de ficheros KML descargados del Catastro.
 - La información adicional de las parcelas se rellena en el fichero 'parcelas.csv'
 - Los puntos de interés se configuran en el fichero 'points.csv'
 - Para la correcta visualización es necesario tener al APIKey de Google.
