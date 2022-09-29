Se están ejecutando 2 contenedores:
  - nicopaez/jobvacancy-ruby:1.3.0
  - postgres:14.4-alpine

Se está definiendo el contenedor nicopaez/jobvacancy-ruby:1.3.0, que setea las variables de ambiente PORT, RACK_ENV y DATABASE_URL, depende de db y bindea el puerto 3000 del contenedor al puerto 3000 del host

En el caso de postgres:14.4-alpine, se define la variable de ambiente POSTGRES_PASSWORD

Ambos se comunican entre sí mediante el puerto 5432, ya que jobvacancy accede a la db mediante la URL definida en DATABASE_URL