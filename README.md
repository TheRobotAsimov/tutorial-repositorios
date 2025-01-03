# Tutorial de Git y GitHub

Probablemente ya hayas utilizado ***GitHub*** por requisito de tu proyecto de Estadía, pero esta es una herramienta que va mucho más allá de eso❗. Aprender a dominar ***GitHub*** es un <span style="color:cyan;">*must to* (tienes que)</span> si estás pensando en entrar al mundo profesional de desarrollo en equipo de software 👨‍💻. Por eso traigo este intento de tutorial para que afiances más tus bases en ***GitHub***.

Con ***GitHub*** olvidense de estarse pasando las EPs por whats <img src="images/WhatsApp-HH.png" alt="git" width="25px" style="vertical-align: middle;"> o por gmail <img src="images/gmail.png" alt="git" width="20px" style="vertical-align: middle;"> y estar comprimiendo y descomprimiendo .zip's <img src="images/zip.png" alt="git" width="20px" style="vertical-align: middle;"> o estarse saboteando mientras todos editan el mismo replit <img src="images/replit.png" alt="git" width="25px" style="vertical-align: middle;"> 

>***GitHub*** es la manera más eficiente de trabajar en equipo (y por ello al inicio puede costar un poco, pero vale la pena).

## 1. Introducción
Para ver ***GitHub***, primero debemos entender qué es ***Git***.

### <img src="images/git.png" alt="git" width="25px" style="vertical-align: middle;"> Git

>***Git*** es una tecnología que permite guardar un registro de todas las versiones de tu proyecto de software a lo largo de su desarrollo. 

Es decir, con ***Git*** puedes ver cómo lucía tu código al iniciar tu proyecto, cómo lucía dos dias antes o cómo lucía antes de que alguien de tu equipo se le ocurriera meterle mano y provocar que ya ni compile, faltando un día para la entrega ⏱️❗. Con ***Git*** tienes todo el <u>historial de cómo ha ido evolucionando tu código</u> y puedes regresar a cualquiera de esas versiones como si de una máquina del tiempo se tratara 👨‍🔬.

![Linea de tiempo de Git](images/linetime.png)

Pero no siempre es tan simple como una línea recta. Puede tener diferentes ramas, como si de <span style="color:cyan;">universos paralelos</span> se tratase 🌌. Pero eso lo vemos luego.

![Ramas de Git](images/git-branches-merge.png)

Mientras quedense con que ***Git*** es una herramienta que te permite tener un historial de las distintas versiones de tu proyecto y regresar a cualquier versión en cualquier momento.

### <img src="images/github.png" alt="git" width="25px" style="vertical-align: middle;"> GitHub

>***GitHub*** es una plataforma en línea que utiliza ***Git*** para almacenar y gestionar proyectos de manera <span style="color:cyan;"><u>*colaborativa*</u></span>.

Es muy útil para trabajar en equipo, ya que permite a varios desarrolladores trabajar en un mismo proyecto al mismo tiempo de manera segura porque ***GitHub*** ofrece herramientas para revisar 🔍 y discutir 🗣️ los cambios realizados en el código 👨‍💻.

En resumen (que no se note el chat jaja), los beneficios de usar ***Git*** y ***GitHub*** incluyen:
- [x] Mantener un historial de cambios. 🔍
- [x] Facilitar la colaboración entre múltiples desarrolladores. 🤝
- [x] Permitir la recuperación de versiones anteriores del proyecto. ⏪

También es importante saber que ***Git*** y ***GitHub*** no son lo mismo:
- ***Git*** es de uso local (guarda el historial del proyecto en tu compu) 🏠.
- ***GitHub*** es de uso remoto (guarda el historial en la nube) 🌐.

## 2. Cómo usarlo ⁉️

Muy bonito y todo, pero ¿cómo se usa? Aquí les dejo una guía rápida de cómo pueden empezar a utilizar ***Git*** y ***GitHub*** 🏃.

Recuerden que con ***GitHub*** tendremos el <u>proyecto en internet</u> que todos los integrantes del equipo podrán ver y modificar. 

Con ***Git*** tendremos una <u>copia local</u> de ese proyecto en nuestra computadora para poder trabajar en él.

>Apartir de ahora en vez de decir *proyecto*, diremos <span style="color:cyan;">*repositorio*</span> y en lugar de copiar, diremos <span style="color:cyan;">clonar</span>.

### Instalar GitHub Desktop <img src="images/github-desktop-logo.png" alt="git" width="40px" style="vertical-align: middle;"> 

Por lo popular que es este *workflow* (flujo de trabajo) de ***Git*** y ***GitHub***, ya existen herramientas que facilitan su uso. Una de ellas es ***GitHub Desktop***, que es una interfaz gráfica para usar ***Git*** y ***GitHub***. Pueden descargarla [aquí](https://desktop.github.com/).

Al instalarla, les pedirá que inicien sesión con su cuenta de ***GitHub***. Si no tienen, les da la opción de crear una.

Como yo ya tengo una cuenta, le daré en <span style="background-color: #007bff; color: #fff; padding: 5px 10px; border-radius: 5px;">Sign in to GitHub.com</span>

![GitHub Desktop](images/ghd1.jpg)

***Git*** requiere que le digas quién eres para que pueda registrar los cambios que hagas en el proyecto. Así que les pedirá poner su nombre y correo electrónico (Por defecto, usará el nombre y correo electrónico que tengan en su cuenta de ***GitHub***).

Y le dan en <span style="background-color: #007bff; color: #fff; padding: 5px 10px; border-radius: 5px;">Finish</span>

![GitHub Desktop](images/ghd2.jpg)

Después de eso, ya les aparecerá la pantalla principal de ***GitHub Desktop***.

![GitHub Desktop](images/ghd3.jpg)

Te da 4 opciones:
- [x] Crear un repositorio local y subirlo a GitHub a modo de tutorial.
- [ ] Clonar un repositorio que ya exista en GitHub.
- [ ] Crear un repositorio local.
- [ ] Abrir un repositorio que ya exista en tu computadora.

Haremos el tutorial. Entonces seleccionamos <span style="background-color: #007bff; color: #fff; padding: 5px 10px; border-radius: 5px;">Create a tutorial repository</span>

![GitHub Desktop](images/ghd4.jpg)

Les abrirá este mensaje. Prácticamente les dice lo que les vengo diciendo, que va a crear un repositorio en su computadora y que lo va a subir a ***GitHub***. Le dan en <span style="background-color: #007bff; color: #fff; padding: 5px 10px; border-radius: 5px;">Continue</span>

### Crear Repositorio

¿Qué creen? ya crearon su propio repositorio local 🙌 (lo pueden buscar en su compu en *Documentos/GitHub/desktop-tutorial*). 

![GitHub Desktop](images/gh2.jpg)

Ya hasta lo subieron a ***GitHub*** (todo automáticamente jaja). Si no me creen, vayan a su cuenta de ***GitHub*** y verán que ya tienen un repositorio llamado <span style="color:#0099FF;">desktop-tutorial</span>.

![GitHub Desktop](images/gh1.jpg)

*<div style="text-align: center;">(Simón, soy ese blanco albino)</div>*

>Verán que del lado derecho dice `Private`. Eso significa que solo ustedes pueden verlo 🕵️‍♂️. Si quieren que todos lo vean, debería decir `Public` 🌐.

### Crear ramas (o branches en inglés)

Recuerdan que les dije que pueden tener diferentes <span style="color:cyan;">universos paralelos</span> de su proyecto, bueno en ***Git*** cada universo se conoce como <span style="color:cyan;">rama (branch)</span>. La rama principal se suele llamar <span style="color:cyan;">*main*</span> o <span style="color:cyan;">*master*</span>.
El *modus operandi* es que cada vez que quieran hacer un cambio en su proyecto, creen una rama nueva.

![GitHub Desktop](images/git-branches-merge.png)

Si todo sale bien, pueden fusionar su rama con la rama principal. Si no, pueden borrar esa rama y seguir trabajando en la rama principal. El chiste es proteger la <span style="color:cyan;">main branch</span> de cambios que puedan romper el proyecto 🛡️.

![GitHub Desktop](images/loki.jpg)

Eso es lo que nos pide el tutorial, que creemos una rama nueva. Entonces la creamos (damos clic en <span style="color:#0099FF;">*New branch*</span>):

![alt text](images/ghd5.jpg)

Le damos un nombre y le damos en <span style="background-color: #007bff; color: #fff; padding: 5px 10px; border-radius: 5px;">Create branch</span>

![alt text](images/ghd6.jpg)

### Hacer cambios

Ahora nos pedira que hagamos cambios en nuestro proyecto.

>Cuando creamos el repositorio de tutorial, también nos creó el archivo `README.md` (Este archivo suele ser usado para explicar de que trata un repositorio y de hecho ahora mismo estas leyendo un archivo `README.md`).

![alt text](images/gh3.jpg)

Entonces abrimos el archivo `README.md`. Damos clic en <span style="color:#0099FF;">Open editor</span> para abrir el archivo.

![alt text](images/ghd7.jpg)

Este es el contenido del archivo:

![alt text](images/ghd8.jpg)

El lado izquierdo es el archivo original y el lado derecho es como se visualizará en **GitHub**

>Los archivos `.md` *(o markdown)* son archivos especiales para hacer anotaciones.

![alt text](images/ghd9.jpg)

Modificamos el archivo. Podemos escribir algo adicional o borrar algo de lo que ya estaba. En mi caso, agregué mi *username* en la línea 6.

![alt text](images/ghd10.jpg)

***GitHub Desktop*** es muy perspicaz y detecta que hicimos cambios en el archivo. Ahora haremos lo que se denomina *<span style="color:cyan;">commit</span>*, o sea guardar los cambios para que se quede registrado en el historial.

### Guardar cambios (commit)

Cada vez que hagan un *<span style="color:cyan;">commit</span>* es obligatorio agregar una descripción de los cambios que hicieron. En este caso, puse *"Agregué mi username en `README.md`"*. 

Le dan en <span style="background-color: #007bff; color: #fff; padding: 5px 10px; border-radius: 5px;">Commit to **<nombre de su rama\>**</span>.

![alt text](images/ghd11.jpg)

### Subir cambios a GitHub (push)

Excelente, ya agregaron una nueva versión de su proyecto de manera local. Ahora toca subir esos cambios a ***GitHub***. A eso se le llama <span style="color:cyan;">*push*</span>.

Para esto denle clic en <span style="color:#0099FF;">Publish branch</span>.

![alt text](images/ghd12.jpg)


### Fusionar ramas (*pull request* y *merge*)

>Ya subieron su cambio a ***GitHub***, pero recuerden que crearon una rama y los cambios aún no están en la rama principal.

Para fusionar las dos ramas, deben hacer un <span style="color:cyan;">pull request</span> o solicitud de fusión.

![alt text](images/ghd13.jpg)

Les abrirá la siguiente ventana:

![alt text](images/ghd14.jpg)

Aquí es donde se suele discutir los cambios que se hicieron 🔍 (muy esquizo ahorita porque estan solitos en este proyecto). Se pueden hacer varias cosas aquí pero por ahora solo le dan en <span style="background-color:rgb(0, 145, 48); color: #fff; padding: 5px 10px; border-radius: 5px;">**Create pull request**</span>.

>***GitHub*** analiza los cambios que hicieron y, si todo está bien, les da la opción de fusionar (merge) los cambios a la rama principal.

Le dan en <span style="background-color:rgb(0, 145, 48); color: #fff; padding: 5px 10px; border-radius: 5px;">**Merge pull request**</span>.

![alt text](images/ghd15.jpg)

Confirmamos el merge

![alt text](images/ghd16.jpg)

Y listo 🙌. Ahora nos da la opción de borrar la rama que creamos, pero ya no me importa que hagan aquí, ya hicieron todo lo que tenían que hacer. (Le dan en *"Delete branch"*)

![alt text](images/ghd17.jpg)

Si le dan en *"desktop-tutorial"* o en *"Code"* les llevará a la página principal de su repositorio en ***GitHub***.

![alt text](images/ghd18.jpg)

Verán que se guardó el *commit* que hicieron.

![alt text](images/ghd19.jpg)

## 3. Fin

Aún hay más cosas que decir sobre todo esto que vimos y mucho más sobre lo que no hemos visto.
Pero por lo menos ya han dado sus primeros pasos en este mundo de ***GitHub*** 👣 y ahora están un paso más cerca de ser un desarrollador profesional 👏.

Pueden buscar tutoriales más avanzados en internet 👨‍💻 o seguir experimentando con ***GitHub Desktop***. También pueden intentar usar ***Git*** desde la terminal, que es la forma más pura de usar ***Git***.

>Incluso si veo interés podríamos hacer un repositorio entre todos para que practiquen más.
