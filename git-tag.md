#git tag 
Lista las etiquetas existentes

### git tag nombre_etiqueta
Lista las etiquetas en orden alfabético.

## git tag  -a nombre_etiqueta  -m "mensaje de la etiqueta"
Etiqueta anotada. Se guardan en la base de datos de git como objeetos enteros. Tienen un checksum; contienen el nombre del etiquetador, correo  y fecha; tienen un mensaje asociado.

## git tag -l 'v2.*'
Lista las etiquetas que coincidan con el patron especificado