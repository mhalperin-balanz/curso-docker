# Instrucciones

- Clonar el repositorio
- Ejecutar en la carpeta del repo
  - ````docker build -t ejercicio06 .````
  - ````docker run -p 8080:8080 ejercicio06````
- Ya se puede ver la web en ````localhost:8080````

- Para publicar la imagen en Dockerhub
  - ````docker login````
  - ````docker tag ejercicio06 <username>/ejercicio06````
  - ````docker push <username>/ejercicio06````

https://hub.docker.com/repository/docker/matiashalperin/ejercicio06