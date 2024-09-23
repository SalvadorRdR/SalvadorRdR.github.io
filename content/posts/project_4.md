+++
title = 'Estación meteorológica con comunicación satelital'
featured_image = "/images/estacion.jpeg"
date = 2024-09-01T02:02:06-05:00
+++

Como parte del curso de **Sistemas Digitales** en mi carrera de Ingeniería Física, diseñé e implementé una **estación meteorológica de bajo costo basada en Arduino**, capaz de medir diversos parámetros ambientales, tales como la humedad del suelo, humedad relativa, temperatura, presión atmosférica y altura relativa al nivel del mar.

Para la adquisición de datos, utilicé los siguientes sensores:

* **Higrómetro**: Para medir la humedad del suelo.
* **DHT22**: Para la humedad relativa y temperatura.
* **BMP180**: Para la presión atmosférica y la altura.

 {{< figure src="/images/estacion_final.png" >}}

Los datos recolectados fueron transmitidos a la plataforma en la nube **Swarm Hive** mediante un **[transceptor satelital Swarm M138](https://github.com/sparkfunX/Satellite_Transceiver_Breakout__Swarm_M138)** conectado al Arduino Mega. Este sistema permitió la monitorización en tiempo real de los datos, garantizando una comunicación eficiente y confiable entre los sensores y la tecnología satelital.



{{< figure src="/images/estacion2.png" >}}