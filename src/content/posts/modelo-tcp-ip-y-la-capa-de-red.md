---
title: Modelo TCP/IP y la capa de acceso de red
description: "Modelo TCP/IP y la capa de acceso de red"
category:
  - tercer-parcial
tags:
  - Modelo OSI
  - RedesLAN
pubDate: 2023-10-09
cover: src/images/modelo-tcp-ip.png
coverAlt: RedLAN - Blog
author: Omar Camarillo
---

## ¿Qué es una dirección IP y por qué es importante?
'IP' significa Protocolo de Internet , que es el conjunto de reglas que hace posible que los dispositivos se comuniquen a través de Internet . Dado que miles de millones de personas acceden a Internet todos los días, se necesitan identificadores únicos para realizar un seguimiento de quién hace qué. El Protocolo de Internet resuelve esto asignando números de IP a cada dispositivo que accede a Internet.

<img src="https://cf-assets.www.cloudflare.com/slt3lc6tev37/54NvR4ArYd9isJUmbz5wbW/5abc7d8ece3a915683f8ed71d47ea28e/ddos-dns.svg" alt=""/>

La dirección IP de una computadora es como la dirección física de una casa. Si alguien llama a una pizzería para pedir una entrega, debe proporcionar su dirección física. Sin esa dirección, el repartidor de pizzas no tendrá idea de a qué casa entregar la pizza.

Por ejemplo, cuando un usuario escribe un nombre de dominio , como google.com, en un navegador web, se iniciará una solicitud al servidor web de Google solicitando contenido (la página de inicio de Google). Una vez que Google recibe la solicitud, necesita saber dónde enviar el contenido del sitio web. Por este motivo, la solicitud contendrá la dirección IP del solicitante. Utilizando la dirección IP proporcionada, Google puede enviar una respuesta al dispositivo del usuario, que luego mostrará ese contenido en el navegador web del usuario.

El sistema que orquesta todo esto se llama DNS . Funciona como una guía telefónica para direcciones IP para que los usuarios puedan acceder a servicios web utilizando nombres de dominio amigables para los humanos. Cuando un usuario escribe un nombre de dominio como 'facebook.com' en la ventana de su navegador, se inicia una consulta DNS que finalmente conduce a un servidor DNS que traduce el nombre de dominio en una dirección IP.

¿Cómo son las direcciones IP? Estas direcciones tienen un formato diferente según sean IPv4 o IPv6.

## ¿Cuál es la diferencia entre IPv4 e IPv6?
IPv4 e IPv6 son versiones diferentes del Protocolo de Internet. IPv4 se implementó en 1983 y todavía se utiliza en la actualidad. El formato de las direcciones IPv4 es de cuatro conjuntos de números separados por puntos, por ejemplo: '192.0.2.1'. Este es un formato de 32 bits, lo que significa que permite 2 32 , o alrededor de 4,3 mil millones de direcciones IP únicas, lo que resulta no ser suficiente para la cantidad de dispositivos que hay actualmente en Internet. La necesidad de más direcciones IP llevó a la implementación de IPv6.* Las direcciones IPv6 utilizan un formato más complejo que utiliza conjuntos de números y letras separados por dos puntos simples o dobles, por ejemplo: '2001:0db8:85a3:0000:0000:8a2e :0370:7334'. Este formato de 128 bits puede admitir 2128 direcciones únicas. (¡Eso equivale a un número de 39 dígitos!)

IPv6 proporciona algunas otras actualizaciones a IPv4, incluidas mejoras de seguridad y privacidad . A pesar de sus diferencias, tanto IPv4 como IPv6 se han utilizado simultáneamente en la web durante más de una década. Las dos versiones pueden ejecutarse en paralelo, pero se tuvieron que implementar medidas especiales para facilitar las comunicaciones entre dispositivos IPv4 e IPv6. Se tuvo que hacer este compromiso porque gran parte de la web todavía se ejecuta en direcciones IPv4.

*¿Qué pasó con IPv5? IPv5 fue un protocolo de transmisión de datos experimental que nunca se implementó. Utilizaba el mismo formato de 32 bits que IPv4, por lo que no resolvió adecuadamente el problema de no tener suficientes direcciones IP únicas. Por este motivo, IPv6 se convirtió en el sucesor de IPv4.

## ¿Cuál es la diferencia entre IP estáticas e IP dinámicas?
La oferta limitada de direcciones IPv4 llevó a la introducción de la asignación dinámica de direcciones IP, que sigue siendo una práctica muy común. A la mayoría de los dispositivos conectados a Internet se les asignan direcciones IP temporales.

Por ejemplo, cuando un usuario doméstico se conecta a Internet en su computadora portátil, el ISP de ese usuario le asigna una dirección IP temporal de un grupo de direcciones IP compartidas. Esto se conoce como dirección IP dinámica. Esto es más rentable para el ISP que asignar a cada usuario una dirección IP permanente o estática.

<img src="https://cf-assets.www.cloudflare.com/slt3lc6tev37/JwXPPU511S5iPuwimt3vf/d7d9df64e5709e2fc055f566fee2c8fb/dynamic-ip-addresses-isps.svg" alt="" />
