# Parte 1 – Optimización del tamaño de los ficheros
Para reducir el tamaño de la base de datos, una vez importada en SQL Server seguimos estos pasos:  
 - ClickDerecho en la base de datos --> Tasks --> Shrink --> Database/Files (una vez cada opción).  
 - Cambiar los tipos de las columnas cuyo tipo ocupe demasiado espacio para lo que almacenan.  
  
En nuestro caso además de utilizar la herramienta 'Shrink' hemos cambiado el tipo de gran parte de las columnas de char(500) a char() con longitud igual a la máxima longitud de un dato guardado en la columna.  
  
Los archivos de la base de datos sin reducir el tamaño quedan de la siguiente forma:  
![image](https://user-images.githubusercontent.com/114938688/236152587-d7d8c5da-19f1-4109-b832-45c578f53fe6.png)  
Una vez realizados los pasos definidos previamente el tamaño queda reducido en un 53% (IMPRECISO: Esta imagen se ha tomado solo habiendo utilizado el Shrink):
![image](https://user-images.githubusercontent.com/114938688/236155658-fd093a24-68e4-4be4-99ac-7c7e33a32d95.png)  

# Parte 2 – Diccionario de datos
Las tablas de la base de datos SNTBROKER representan ciertos datos, estos son los que hemos encontrado:  

# Parte 3 – Personal Keys
# Parte 4 – Foreign Keys
# Parte 5 – Crawler de YahooFinance
# Parte 6 – Parser de JSON
# Parte 7 – Mejora del script de ejemplo
