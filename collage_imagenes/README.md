# Desafío guiado - Collage de imágenes

Desafío «Collage de imágenes» del módulo 8 del bootcamp Full Stack JavaScript de Talento Digital.

## Descripción

Para realizar este desafío debes haber estudiado previamente todo el material disponibilizado correspondiente a la unidad.

## Requerimientos

1. Integrar express-fileupload a Express. (1 Punto)
2. Definir que el límite para la carga de imágenes es de 5MB. (2 Puntos)
3. Responder con un mensaje indicando que se sobrepasó el límite especificado. (2 Puntos)
4. Crear una ruta POST /imagen que reciba y almacene una imagen en una carpeta pública del servidor. Considerar que el formulario envía un payload con una propiedad “position”, que indica la posición del collage donde se deberá mostrar la imagen. (3 Puntos)
5. Crear una ruta DELETE /imagen/:nombre que reciba como parámetro el nombre de una imagen y la elimine de la carpeta en donde están siendo alojadas las imágenes. Considerar que esta interacción se ejecuta al hacer click en alguno de los números del collage. (2 Puntos)
