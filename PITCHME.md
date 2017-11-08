@title[Introduction]

#### Características del protocolo HTTP

<span class="aside">
  HTTP, de sus siglas en inglés: "Hypertext Transfer Protocol", es el nombre de un protocolo el cual nos permite realizar una petición de datos y recursos, como pueden ser documentos HTML. Es la base de cualquier intercambio de datos en la Web, y un protocolo de estructura cliente-servidor, esto quiere decir que una petición de datos es iniciada, por el elemento que recibirá los datos (el cliente), normalmente un navegador Web.
</span>

---

@title[PITCHME.md]

#### Típica Sesión HTTP

<span class="aside">
  En los protocolos basados en el modelo cliente-servidor, como es el caso del HTTP, una sesión consta de tres fases:<br>
  1. El cliente establece una conexión TCP (o la conexión correspondiente si la capa de transporte corresponde a otro protocolo).<br>
  2. El cliente manda su petición, y espera por la respuesta.<br>
  3. El servidor procesa la petición, y responde con un código de estado y los datos correspondientes.<br>
</span>

---

#### Estableciendo una conexión

<span class="aside">
  En un protocolo cliente servidor, es siempre el cliente el que establece la conexión. Iniciar una conexión en HTTP, implica iniciar una conexión en el protocolo correspondiente a la capa de comunicación subyacente, que normalmente es TCP.
</span>

---

@title[Step 1. Cabecera]

#### Cabeceras protocolo HTTP

<span class="aside">
  Cada petición HTTP que el navegador realiza al servidor, se divide en 2 partes:<br>
  – Las cabeceras (Headers)<br>
  – El cuerpo de la respuesta (Response body)<br>
</span>

---

#### Petición de nuestro navegador:

<span class="aside">
  GET /index.html HTTP/1.1<br>
  Host: www.example.com<br>
  User-Agent: nombre-cliente
</span>

---

#### El servidor responde a nuestra petición:

<span class="aside">
  HTTP/1.1 200 OK<br>
  Date: Fri, 31 Dec 2003 23:59:59 GMT<br>
  Content-Type: text/html<br>
  Content-Length: 1221
</span>

---

@title[Step 2. Cookies]

#### Cookies

<span class="aside">
  Una cookie HTTP, cookie web o cookie de navegador es una pequeña pieza de datos que un servidor envía a el navegador web del usuario. El navegador guarda estos datos y los envía de regreso junto con la nueva petición al mismo servidor. Las cookies se usan generalmente para decirle al servidor que dos peticiones tiene su origen en el mismo navegador web lo que permite.
</span>

---

@title[Step 3. Evolucion]

#### Evolución de HTTP

<span class="aside">
  HTTP es el protocolo en el que se basa la Web. Fue inventado por Tim Berners-Lee entre los años 1989-1991, HTTP ha visto muchos cambios, manteniendo la mayor parte de su simplicidad y desarrollando su flexibilidad. HTTP ha evolucionado, desde un protocolo destinado al intercambio de archivos en un entorno de un laboratorio semi-seguro, al actual laberinto de Internet, sirviendo ahora para el intercambio de imágenes, vídeos en alta resolución y en 3D.
</span>

---

@title[Step 4. Caracteristicas]

#### Características de HTTP 2.0

<span class="aside">
  Muchos consideran a HTTP/2 el reemplazo del protocolo SPDY que desarrollo Google para mejorar el rendimiento de sus servicios en su navegador Chrome, de hecho el protocolo HTTP/2 está basado en algunas de las ideas del protocolo SPDY, el cual actualmente se considera obsoleto pues se ha apostado completamente por el protocolo HTTP/2.
</span>

---

#### Principales ventajas

<span class="aside">
  - SERVER PUSH <br>
  - COMPRESION DE HEADERS <br>
  - FORMATO BINARIO EN LUGAR DE TEXTO
</span>

---
