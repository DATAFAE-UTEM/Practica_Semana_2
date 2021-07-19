# Practica_Semana_2
El objetivo de esta semana es generar una base de datos relativa a información contenida en la pagina de la CMF.

La página tiene su información contenida en formato tabla.  

De esta manera, el scrap realizado con el paquete Selenium, facilita la extracción de estos, a través de la definición de filas y columnas.
Para ello, se genera una definición de columna y fila genérica, ya que la información detallada para cada coordenada de la tabla,
posee esta ubicación definida como base.

Se efecutuó una iteración que recorre todos los elementos por columna y fila.

Adicionalmente, se destaca un modelo que extrae los links contenidos en un url.
Esto se efectuó con el fin de poder descargar ciertos elementos con atributo .pdf.
