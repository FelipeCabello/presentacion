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

@title[Step 1. PITCHME.md]

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

@title[Step 2. Git-Commit]

### <span class="gold">STEP 2. GIT-COMMIT</span>
<br>

```shell
$ git add PITCHME.md
$ git commit -m "New slideshow content."
$ git push

Done!
```

@[1](Add your PITCHME.md slideshow content file.)
@[2](Commit PITCHME.md to your local repo.)
@[3](Push PITCHME.md to your public repo and you're done!)
@[5](Supports GitHub, GitLab, Bitbucket, GitBucket, Gitea, and Gogs.)

---

@title[Step 3. Done!]

### <span class="gold">STEP 3. GET THE WORD OUT!</span>
<br>
![GitPitch Slideshow URLs](assets/images/gp-slideshow-urls.png)
<br>
<br>
#### Instantly use your GitPitch slideshow URL to promote, pitch or present absolutely anything.

---

@title[Slide Rich]

### <span class="gold">Slide Rich</span>

#### Code Presenting for Blocks, Files, and GISTs
#### Image, Video, Chart, and Math Slides
#### Multiple Themes with Easy Customization
<br>
#### <span class="gold">Plus collaboration is built-in...</span>
#### Your Slideshow is Part of Your Project
#### Under Git Version Control within Your Git Repo

---

@title[Feature Rich]

### <span class="gold">Feature Rich</span>

#### Present Online or Offline
#### With Speaker Notes Support
#### Print Presentation as PDF
#### Auto-Generated Table-of-Contents
#### Share Presentation on Twitter or LinkedIn

---

### Go for it.
### Just add <span class="gold">PITCHME.md</span> ;)
<br>
[Click here to learn more...](https://github.com/gitpitch/gitpitch/wiki)
