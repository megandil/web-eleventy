---
title: Vagrant
emoji: 😺
metaDescription: This is a sample meta description. If one is not present in your page/project's front matter, the default metadata.desciption will be used instead.
date: 2019-01-01T00:00:00.000Z
summary: Trabajando con Vagrant
tags:
  - vagrant
  - ssh
---

### Tarea

Queremos automatizar la creación de la siguiente infraestructura usando Vagrant, el esquema que queremos desarrollar, que vemos en la imagen, tiene las siguientes características:

- Es escenario tiene dos máquinas:
    - Router, que está conectada a una red publica y a una red privada (muy aislada). La interfaz de red en la red privada se configura con la IP 10.0.0.1.
    - Cliente: Esta máquina está conectada a la misma red privada que la máquina anterior, en este caso su direccionamiento es 10.0.0.2.
