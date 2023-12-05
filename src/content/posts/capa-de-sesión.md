---
title: Capa de sesion
description: "Consiste de un transponder (dispositivo receptor-transmisor), una estación basada en tierra
que controlar su funcionamiento y una red de usuario, de las estaciones terrestres, que
proporciona las facilidades para transmisión y recepción del tráfico de comunicaciones, a
través del sistema de satélite."
category:
  - tercer-parcial
tags:
  - Cable Cuaxial
  - RedesLAN
pubDate: 2023-10-09
cover: src/images/capa-de-sesión.jpg
coverAlt: RedLAN - Blog
author: Omar Camarillo
---
## ¿Que es?
La capa de sesión se encarga de organizar la conexión entre dos sistemas finales. Para ello, el session layer crea las denominadas sesiones, que ofrecen diferentes servicios. La capa de sesión trabaja estrechamente con sus capas adyacentes en el modelo OSI

## Control de la comunicación en la capa de sesión

La función principal de la capa de sesión es establecer una conexión entre dos sistemas. Dicha conexión se denomina sesión y cada una es única e inequívoca. El control de las sesiones también es responsabilidad de la capa de sesión. La capa puede, por ejemplo, permitir el acceso temporal a otro sistema para controlar la comunicación.

La comunicación, que es llevada a cabo por la capa de sesión del modelo OSI, se establece entre ambas partes, de forma paralela o unidireccional, y se denomina control del diálogo (dialog control). Para la comunicación unidireccional, el session layer puede asignar tokens para poder organizar la secuencia y permitir así un diálogo sin interrupciones.

Los tokens de la capa de sesión del modelo OSI se dividen en cuatro categorías:

- Tokens de datos (Data Token): durante la comunicación unidireccional en modo semidúplex, indican qué equipo puede transmitir y cuándo.
- Tokens de actividad (Activity Major Token): los tokens de actividad dividen una conexión en diferentes actividades. Si una actividad se interrumpe o se cancela, puede reanudarse más tarde en la misma sesión o en otra distinta.
- Tokens de sincronización (Synchronize Minor Token): los tokens de sincronización están numerados del 0 al 999 999 y se utilizan para fraccionar una comunicación. Más adelante obtendrás más información sobre la sincronización a nivel de la sesión.
- Token de finalización (Release Token): los tokens de finalización marcan el final de una sesión.

## ¿Qué servicios presta la capa de sesión del modelo OSI?

Los servicios de la capa de sesión, algunos de los cuales se han mencionado previamente, se ponen a disposición de los procesos de aplicación y persiguen el objetivo de organizar y sincronizar mejor la comunicación. Los servicios de la capa de sesión se utilizan cuando esta solicita a la capa de transporte una conexión con un segundo ordenador (nivel 4). Los diferentes servicios se agrupan en unidades funcionales. La Organización Internacional de Normalización (ISO), que también ayudó a desarrollar el modelo OSI, propone la siguiente clasificación para las unidades funcionales. La combinación adecuada la determinan ambas partes antes de establecer la sesión.

- Basic Combined Subset (BCS): compatible con el kernel, semidúplex y dúplex
- Basic Synchronized Subset (BSS): compatible con el kernel, semidúplex, negotiated release, puntos de sincronización mayores y menores y resincronización
- Basic Activity Subset (BAS): compatible con el kernel, semidúplex, puntos de sincronización menores, excepciones y gestión de actividades
