# Instrucciones

- Clonar el repositorio
- Ejecutar en la carpeta del repo
  - ````docker build -t ejercicio04 .````
  - ````docker run -p 8080:8080 ejercicio04````
- Ya se puede ver la web en ````localhost:8080````

- Para publicar la imagen en Dockerhub
  - ````docker login````
  - ````docker tag ejercicio04 <username>/ejercicio04````
  - ````docker push <username>/ejercicio04````

https://hub.docker.com/repository/docker/matiashalperin/ejercicio04