# La version de PHP puede ser modificada aqui.
FROM php:7.4-cli

# Imagen mucho mas ligera
# FROM php:7.2.30-zts-alpine

# Creamos un directorio para trabajar
WORKDIR /usr/src/app

# Copiamos la carpeta donde esta ubicado el codigo
COPY src /usr/src/app

# Iniciamos el servidor PHP corriendo el index.php
CMD [ "php", "./index.php" ]