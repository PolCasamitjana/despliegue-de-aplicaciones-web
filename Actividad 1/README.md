3. Analiza los headers de las peticiones cuando inicias sesión en el Moodle y comprende
cómo se obtiene el token. Para ello, necesitamos saber de dónde salen TODOS los
datos sensibles que se envían.

![token](https://github.com/PolCasamitjana/despliegue-de-aplicaciones-web/assets/144775621/9b7030a1-d328-4924-8258-9dc91f5d5969)

4. ¿A qué puerto se reciben normalmente las peticiones del protocolo HTTP? ¿A qué
capa del modelo TCP/IP se encuentra el protocolo HTTP? ¿Y los protocolos TCP,
UDP, e IP?

Las peticiones del protocolo HTTP se reciben normalmente en el puerto 80. El protocolo HTTP se encuentra en la capa 4.
Los protocolos TCP en la capa 4.
Los protocolos UPD en la capa 4.
Los protocolos IP en la capa Red, la 3.

5. ¿Cuál es el significado de la siguiente respuesta de un servidor?
HTTP/1.1 302 Found
Location: http://www.example.com/test/index2.php

"302 Found" con "Location" se utiliza para redirigir al cliente a una nueva ubicación.

6. Utilizando el filtro de captura para la interfaz de red de Wireshark, analiza la petición
al host: www.google.com. Mostrando la cabecera IP, la dirección IP de tu ordenador y
la del servidor. Comprueba que, poniendo esa IP en el navegador, accedas a Google.

