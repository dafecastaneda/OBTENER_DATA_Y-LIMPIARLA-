# OBTENER_DATA_Y-LIMPIARLA-
Este proyecto es un tutorial para leer data 

## Leer Archivos en Excel 
Excel puede ser probablemente uno de los formatos mas usados para compartir informacion (data)
esto se da por que una gran cantidad de personas usan las hojas de calculo. Cuando utilizas un programa para analizar data como "R", necesitar ser capas de extraer esta infromacion 

### ejemplo practico
pasos 
1. primero vamos a descar la información en un archivo de excel 

  if(!file.exist("data")) { #aqui lo que hacemos es revisar si el nombre ya existe
    dir.create ("data")    # si no esxite, lo vamos a crear 
      }
  datos_baltimore_camaras<- "https://data.baltimorecity.gov/Transportation/Baltimore-Fixed-Speed-Cameras/dz54-2aru#Download" # luego le agregamos un nombre al URL que vamos a usar 
  
 download.file(fileUrl,destfile= ". /data/ cameras.xlsx",method = "curl"
 
