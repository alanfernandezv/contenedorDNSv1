#Docker-compose.yml

Descripciones de las opciones del docker-compose.yml:
- version
 - services
    - bind
       - image
        - ports
         - volumes
 - volumes
    - nombresvolumen

    - version:Colocamos la version de docker-compose que necesitemos
    - services: Aqui meteremos todas las opciones
      - nombre: Aqui ponemos el nombre
      - image: Aqui ponemos la imagen que vamos a usar
      - ports: Aqui ponemos los puertos que vamos a usar
      - volumes: Aqui ponemos nuestros volumenes y las rutas necesarias para la imagen
    - volumes: Aqui creamos nuestros volumes

     

