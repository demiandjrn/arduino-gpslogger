Monitoriza las tramas (formato NMEA) enviadas por un GPS conectado por el puerto serie y las guarda en una memoria microSD para su posterior analisis o uso en otros programas.

**Notas:**

  * Unicamente se guarda la trama GPGGA
  * El programa no envia informacion por el puerto serie, solo lee.
  * El fichero donde se guarde la traza de las tramas debe estar creado en el raiz de la tarjeta SD, el nombre debe ser en formato 8+3 y almenos tener un caracter. Esto es una limitacion actual de la liberia [Arduino-FileLogger](http://code.google.com/p/arduino-filelogger/) usada para guardar los datos en la memoria SD.

**Hardware probado**

  * Arduino duemilanove (ATmega328)
  * Arduino Pro Mini 3.3v 8Mhz (ATmega168)
  * Libelium microSD
  * GPS USGlobalSat EM-406
  * San Jose Navigation FV-M8 (EB-85)


---


Creditos:

  * Para el desarrollo se ha usado como referencia el código del [Ardupilot](http://diydrones.com/profiles/blogs/ardupilot-home-page) de [Jordi Muñoz](http://diydrones.com/profile/jordii).