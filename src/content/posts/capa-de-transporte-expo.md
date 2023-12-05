---
title: Capa de tranposrte 2
description: "Capa de tranposrte 2."
category:
  - tercer-parcial
tags:
  - Modelo OSI
  - RedesLAN
pubDate: 2023-10-09
cover: src/images/capa-de-transporte.jpg
coverAlt: RedLAN - Blog
author: Omar Camarillo
---
## ¿Que es?
La capa 4 es la responsable de las comunicaciones de extremo a extremo entre dos dispositivos. Esto implica, antes de proceder a ejecutar el envío a la capa 3, tomar datos de la capa de sesión y fragmentarlos seguidamente en trozos más pequeños llamados segmentos. La capa de transporte del dispositivo receptor es la responsable luego de rearmar tales segmentos y construir con ellos datos que la capa de sesión pueda consumir.

La capa de transporte también es responsable del control de flujo y el control de errores. El control de flujo determina una velocidad óptima de transmisión para garantizar que un emisor con una conexión rápida no abrume a un receptor con una conexión lenta. La capa de transporte realiza un control de errores en el extremo receptor al garantizar que los datos recibidos estén completos y solicitar una retransmisión si no lo están.
