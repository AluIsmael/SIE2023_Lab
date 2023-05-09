# Parte 1 – Optimización del tamaño de los ficheros
Para reducir el tamaño de la base de datos, una vez importada en SQL Server seguimos estos pasos:  
 - Cambiar los tipos de las columnas de char(500) a varchar(500), de forma que el almacenamiento es dinámico pero el tamaño máximo igual asegura que no haya problemas de espacio en ninguna tabla.  
 - ClickDerecho en la base de datos --> Tasks --> Shrink --> Database/Files (una vez cada opción).  
  
El tamaño de la base de datos sin reducir queda de la siguiente forma:  
![image](https://github.com/AluIsmael/SIE2023_Lab/assets/114938688/a3072aaf-2f8e-4922-8ee3-ef0f52d15798)  

#TODO: Volver a realizar todos los procedimientos y documentar el orden  
Una vez realizados los pasos definidos previamente el tamaño queda reducido en un 53% (IMPRECISO: Esta imagen se ha tomado solo habiendo utilizado el Shrink):  
![image](https://user-images.githubusercontent.com/114938688/236155658-fd093a24-68e4-4be4-99ac-7c7e33a32d95.png)  

# Parte 2 – Diccionario de datos
Las tablas de la base de datos SNTBROKER representan ciertos datos, estos son los que hemos encontrado:  

# Parte 3 – Personal Keys
# Parte 4 – Foreign Keys
# Parte 5 – Crawler de YahooFinance
# Parte 6 – Parser de JSON
# Parte 7 – Mejora del script de ejemplo
