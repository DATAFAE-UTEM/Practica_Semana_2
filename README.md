# Practica_Semana_2
El objetivo de esta semana es generar una base de datos relativa a informaci�n contenida en la pagina de la CMF.

La p�gina tiene su informaci�n contenida en formato tabla.  

De esta manera, el scrap realizado con el paquete Selenium, facilita la extracci�n de estos, a trav�s de la definici�n de filas y columnas.
Para ello, se genera una definici�n de columna y fila gen�rica, ya que la informaci�n detallada para cada coordenada de la tabla,
posee esta ubicaci�n definida como base.

Se efecutu� una iteraci�n que recorre todos los elementos por columna y fila.

Adicionalmente, se destaca un modelo que extrae los links contenidos en un url.
Esto se efectu� con el fin de poder descargar ciertos elementos con atributo .pdf.
