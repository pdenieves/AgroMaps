# AgroMaps - Google Maps as a help for agriculture

El uso de mapas interactivos y por satélite son de gran ayuda en la administración y control de parcelas y en la gestión de explotaciones agrarias y forestales. 

Con este proyecto exploraré las diferentes posibilidades y retos técnicos para la visualización de cultivos y el tratamiento de datos geográficos. Para el mapa sobre el que trabajar será Google Maps. Iré subiendo a este repositorio las diferentes versiones y módulos de software, principalmente en **Python**.


Notas de la *primera versión*:
 - El código está desarrollado en un notebook de Jupyter (Python)
 - Sobre el mapa se visualizan las parcelas y puntos de interés.
 - Los colores de las parcelas corresponden el tipo de cultivo o al propietario, según el parámetro 'mode'.
 - Las coordenadas de las parcelas se extraen de ficheros KML descargados del Catastro.
 - La información adicional de las parcelas se rellena en el fichero 'parcelas.csv'
 - Los puntos de interés se configuran en el fichero 'points.csv'
 - Para la correcta visualización es necesario tener al APIKey de Google.


Notas de la *segunda versión*:
 - Se ha separado en diferentes notebooks la generación de los datasets que luego se visualizarán.
 - Los datasets se vuelcan en formato Pickle.
 - Se ha añadido la carga de markers.
 - El html generado se puede abrir desde cualquier navegador, incluso desde el movil.
 - Para cada elemento se despliega una ventana con la información referente a la parcela, punto de interés o marker.
 ![image](https://user-images.githubusercontent.com/83430122/193652650-3b1345e4-0a18-4cc7-adcb-ba28f08d9d9a.png)
