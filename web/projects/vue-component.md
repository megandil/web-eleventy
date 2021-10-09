---
title: Ansible
emoji: 🗓
metaDescription: This is a sample meta description. If one is not present in your page/project's front matter, the default metadata.desciption will be used instead.
date: 2019-01-01T00:00:00.000Z
summary: Trabajando con Ansible
tags:
  - yaml
---

### Tarea

- Debes crear un playbook que realice las siguientes tareas de forma automática:

    - Crear un usuario en el servidor remoto que tenga tu nombre.
    - Descarga el fichero desde la url https://wordpress.org/latest.zip.
    - Descomprime ese fichero en el home del usuario creado anteriormente.
    - Instala el paquete mariadb.
    - Crea una base de datos que se llame tunombre_wordpress.
    - Crea un usuario que se llame my_nombre que tenga privilegios sobre la base de datos.
    - Clona el repositorio: https://github.com/josedom24/ansible_ejemplos.git en el home del usuario que hemos creado en el primer punto.