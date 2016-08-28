#DIFERENCIA ENTRE soft y mixed

###Soft

El comando soft no toca el indice del archivo o el árbol de trabajo en lo absoluto
(pero al igual que los otros comandos restablece la cabeza al commit deseado).
Y al igual que el commit, deja todos los cambios modificados. Este comando guarda
memoria de que se realizo un reset y se regreso a un punto en especifico (los cambios
de los commits posteriores  quedan en stage).

###Mixed

El comando mixed modifica el indice pero no el árbol y conserva todos los archivos
modificados pero no asegurados como con el commit, ademas este comando enviá un mensaje
de alerta de lo que no se actualizado. A diferencia de soft mixed no recuerda que hubo 
después del commit al que se le indico regresar (los cambios no quedan en stage).
