---
title: Cable de enlace de datos.
description: "La capa de enlace es la
segunda capa del modelo
OSI y se encarga de
transmitir los bits de los
paquetes de datos sin
errores."
category:
  - tercer-parcial
tags:
  - Modelo OSI
  - RedesLAN
pubDate: 2023-10-09
cover: "../../image/capa-de-enlace-de-datos.jpg"
coverAlt: RedLAN - Blog
author: Omar Camarillo
---
### ¿Que es?
La capa de enlace es la
segunda capa del modelo
OSI y se encarga de
transmitir los bits de los
paquetes de datos sin
errores.

### ¿QUE CAPA RESIVE Y TRANSMITE DATOS?
La capa que transmite los datos es la capa de
enlace, la cual también se conoce como capa
Se encarga de transmitir y recibir los
paquetes de datos entre los nodos en una red
de computadoras. También controla el flujo de
datos, retransmite los paquetes de datos
cuando hay errores y mantiene registros de
direcciones de destino y origen.

### Servicio sin acuse y sin conexión.
La maquina fuente envia marcos
independientes a la maquina destino sin
esperar que los reconozca o acuse el
recibo. No se establece conexión de
antemano ni se libera después. Si se pierde
un marco por ruido no se intenta
recuperarlo en la capa de enlace de datos.
Esta clase de servicio es apropiada cuando
la taza de errores es muy baja , para el
trafico en tiempo real , como la voz.

### Servicio con acuse y sin conexión.
Cada marco enviado es reconocido
individualmente, así el transmisor sabe si el
marco ha llegado bien o no, si no ha
llegado en un tiempo especificado, puede
enviarse de nuevo. El problema con esta
estrategia es que los mensaje tardan
mucho en pasar. Este servicio es útil en
canales inestables, como los de los
sistemas inalámbricos

### Prpotocolos
- AppleTalk
- BGP (Border Gateway Protocol: protocolo
de frontera de entrada).
- EGP (Exterior Gateway Protocol: protocolo
de entrada exterior).
- ICMP (Internet Control Message Protocol
protocolo de acceso a la red).
- IGMP: protocolo de la gerencia del grupo de Internet.

### FUNCIONES DE LA CAPA DE DATOS
- Delimita marcos
- Mantiene la integridad de los marcos
- Provee transparencia de datos
- Detección de errores
- Retransmisión de Marcos para recuperarse
de errores
- Permite el control de flujo
- Supervisa las funciones de enlace

### Caracteristicas 

- Establece conexiones de datos
entre aplicaciones y transfiere
datos entre aplicaciones
- Hace las conexiones punto a punto
- Asegura que el flujo de datos se
enviará de manera eficiente y
correcta

<a href="" download="expo" class="btn-download-post">Descargar Exposición</a>
