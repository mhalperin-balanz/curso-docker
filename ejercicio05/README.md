HEALTHCHECK: Indica a Docker una manera de testear el contenedor para verificar que sigue funcionando correctamente.

ONBUILD: Cuando la imagen donde se encuentra se use como base de otra imagen, va a actuar de trigger y va a ejecutar el comando que le indiquemos.

VOLUME: Crea un directorio sobre el que se va a montar un volumen para persistir datos más allá de la vida del contenedor.