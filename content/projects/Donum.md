---
title: "Donum generador de proformas"
date: 2022-03-01T16:15:58-05:00
---

# Tabla de contenido
1. [Descripción general](#descripción-general)
3. [Tecnologias](#tecnologías-usadas)
    1. [GUI](#gui)
    2. [Base de datos](#base-de-datos)

## Descripción general
Este proyecto fue creado por encargo de la fundación/clínica DONUM en Cuenca-Ecuador. Dentro de los requisitos del cliente tenemos: Administrar productos y servicios; generar proformas; debe poder ejecutarse en al menos 5 ordenadores,  no necesariamente en la misma red; generar informes sobre disponibilidad de producto; lanzar alertas cuando no existan productos.

## Tecnologías usadas
- Motor de Base de datos: PostgreSQL
- Herramienta de diseño de base de datos: [SqlDBM](https://sqldbm.com)
- Lenguaje de programación: Python
- Librerias principales: psycopg2, PyQt5
- PaaS: [Heroku](https://www.heroku.com
)
    
### GUI
La interfaz gráfica fue creada a través de la herramienta Qtdesign y posteriormente programada usando PyQt5
### Base de datos
A través de Heroku se creo una base de datos PostgreSQL

![](https://i.imgur.com/3tLE5Cl.png)
