<!-- hide -->
# El Post de Instagram 
<!-- endhide -->
Instagram es una de las interfaces de usuarios más populares del mundo, este es el primero de los tres ejercicios que te harán replicar las partes más importantes y difíciles de Instagram.com

En este caso, estamos empezando con una sola publicación(post).


## 🌱  ¿Cómo iniciar este proyecto?

No clones este repositorio. El primer paso para comenzar a codificar es clonar el [html boilerplate](https://github.com/4GeeksAcademy/html-hello) en tu computador local o con Gitpod.

a) Si usas Gitpod (recomendado) puedes clonar el boilerplate [clic aquí](https://github.com/4GeeksAcademy/html-hello).

b) Si trabajas localmente, escribe el siguiente comando en tu terminal: 

```sh
git clone  git clone https://github.com/4GeeksAcademy/html-hello
```

💡 Important: Remember to create a new repository, update the remote (`git remote set-url origin <your new url>`), and upload the code to your new repository using `add`, `commit` and `push`.

## Instrucciones

Vamos a replicar [esta imagen](https://github.com/breatheco-de/exercise-instagram-post/blob/master/preview.png?raw=true). Primero, preparemos nuestro projecto a continuación:

![Example Picture](https://github.com/breatheco-de/exercise-instagram-post/blob/master/preview.png?raw=true)

 - [ ] Creamos los archivos HTML y CSS en nuestro editor de codigo. SI estas usando Visual Studio Code, dentro de la carpeta en donde quieras guardar este proyecto, puedes crear ambos archivos dando click en el boton “New File…” como sigue:

![Creating first files](https://i.imgur.com/bVhCZs2.png)

![Files created](https://i.imgur.com/ISoPVl7.png)

 - [ ] Agrega la estructura basica HTML en tu archivo HTML. Si estas usando Visual Studio Code, puedes escribir `!` + Enter lo cual agregaria dicha estructura

![HTML structure 1](https://i.imgur.com/mnB0hER.jpg)

![HTML structure 2](https://i.imgur.com/8PBtZdT.jpg)

 - [ ] Cambia el `<title>` dentro del tag `<head>` a “Instagram Post” y agrega la hoja de estilos **styles.css** tambien dentro del tag `<head>` como sigue:

![HTML structure 3](https://i.imgur.com/5v7kuvU.jpg)

Este proyecto utiliza la fuente Roboto de Google Fonts y utiliza los iconos de Font Awesome, para importar la fuente Roboto de Google Fonts a tu codigo, procedemos como sigue:

 - [ ] Visita [https://fonts.google.com/](https://fonts.google.com/), escribe "Roboto" en la barra de busqueda y selecciona la fuente Roboto debajo:
 
![Google Fonts 1](https://i.imgur.com/zjVBN8f.jpg)

 - [ ] Una vez estes en la pagina de dicha fuente, desliza hacia abajo donde podras encontrar la seccion de estilos y selecciona uno de los estilos dando click en el boton "+" el cual se encuentra del lado derecho de los estilos, para este proyecto usaremos el estilo “Regular 400”:

![Google Fonts 2](https://i.imgur.com/Ir51P9o.png)

 - [ ] Luego de seleccionar el estilo, hacemos click en el boton “View selected families” que se encuentra en la esquina superior derecha de la pagina el cual nos desplegara la ventana de “Selected Family” a la derecha. Aqui tendremos que copiar el codigo indicado en las siguientes imagenes en nuestro archivo HTML, siendo mas especifico, dentro del tag `<head>` como sigue:

![Google Fonts 3](https://i.imgur.com/xhUJetI.jpg)

![Google Fonts 4](https://i.imgur.com/GU8bqQ0.png)

![Google Fonts 5](https://i.imgur.com/b4FZ2qJ.png)


Ahora, importemos los iconos de Font Awesome a nuestro codigo (https://fontawesome.com/), 

 - [ ] Ve a https://fontawesome.com/ y crea una cuenta.
 - [ ] Al crear la cuenta, necesitas ir a tu perfil de cuenta y crear un nuevo kit dando click en el boton de "New Kit", puedes tambien crearlo aqui https://fontawesome.com/kits
 - [ ] Con el kit creado, entra en el mismo y copia el codigo que se indica en la siguiente imagen. Este codigo necesita estar pegado dentro del tag `<head>` en nuestro archivo HTML:

![Icons 1](https://i.imgur.com/YhYcFhU.jpg)

![Icons 2](https://i.imgur.com/ejlnj6H.png)

Ya que tenemos listos nuestros archivos HTML y CSS, podemos proceder con la estrategia de este proyecto.
  

## Estrategia

Empezemos por identificar los tags de HTML que estaremos usando para nuestro website, como `<div>`, `<p>`, etc. El siguiente GIF indica la estrategia que seguiremos en las proximas instrucciones:

![Strategy for instagram post](https://github.com/breatheco-de/exercise-instagram-post/blob/master/strategy.gif?raw=true)

 - [ ] Empezemos por crear el primer `<div>`, es recomendado que cualquier primer `<div>` en tu codigo sea el contenedor o container, en donde todos los demas `<div>` estaran contenidos. Entonces, el primer `<div>` sera el container, y lo escribiremos como sigue `<div class=”container”>`:

![Container 1](https://i.imgur.com/UCT8efS.jpg)

 - [ ] Como vemos en el GIF, el color de fondo de nuestro website es negro, por ende nuestro contenedor necesita cubrir todo nuestro website, para hacer esto, necesitamos ir a nuestro archivo CSS y agregar un `margin: 0` a nuestro body completo usando el `*` como selector

![Container 2](https://i.imgur.com/C8X3gNe.jpg)

 - [ ] Luego tenemos que agregar los estilos a nuestro container, agregando el background color, el ancho "width" y altura "height" para cubrir todo nuestro website

![Container 3](https://i.imgur.com/6yTO2a0.jpg)

Ahora, como se ve en el GIF, tenemos un `<div>` llamado post (el rectangulo verde) que contiene 3 `<div>` principales (los rectangulos rojos), que son el header, photo y footer. Procedemos primero a hacer el marco de nuestro post (rectangulo blanco) y lo centramos en nuestro website como sigue:

 - [ ] Necesitamos que nuestro container tenga un `display: flex` y alinear nuestro marco vertical y horizontalmente usando `align-items:  center` y `justify-content:  center` a nuestra clase container class en el archivo CSS.
 - [ ] Necestiamos agregar el tamano de nuestro marco usando `width` y `height` en la clase post en el archivo CSS. Los resultados deben verse de la siguiente forma:

![Post 1](https://i.imgur.com/Gyw5Oeo.jpg)

![Post 2](https://i.imgur.com/o3VCPsL.jpg)

Ahora creemos los 3 `<div>` principales (rectangulos rojos) contenidos en nuestro `<div>` post, que son el header, photo y el footer como sigue:

 - [ ] Agrega los 3 `<div>` principales en el archivo HTML (esta seguro de agregarlos dentro del `<div>` post):

![Main Divs](https://i.imgur.com/TkSqQRx.jpg)

 - [ ] Agrega las clases header, photo y footer en el archivo CSS con su `width` y `height`, esta seguro de agregar los tamanos de acuerdo al tamano del marco de tu post (puedes usar un `width` de 100% en estas 3 clases dado a que el `height` sera el unico valor que variara en tamano). Para ayudarnos en este proceso, podemos agregar un borde solido rojo de 1px para ayudarnos a visualizar como estan quedando y estan siendo distribuidos los `<div>` en nuestro website:

![Main Divs 2](https://i.imgur.com/JXu8Pon.jpg)

![Main Divs 3](https://i.imgur.com/YepRjDf.jpg)


Nota que la suma de los `heights` o alturas de nuestros `<div>` header, photo y footer es igual a la altura del `<div>` nuestro marco blanco del post. Trabajemos ahora en el `<div>` header:

 - [ ] Agrega los 3 `<div>` en el archivo HTML de acuerdo al GIF (asegurate de agregarlos dentro del `<div>` header), los cuales contendran el logo, el titulo/username del post y el icono de 3 puntos, usemos el selector `id` para estos 3 `<div>`

![Header 1](https://i.imgur.com/ng5lrcW.jpg)

 - [ ] Agrega los estilos en el archivo CSS correspondientes a estos 3 `<div>` usando `#` como selector ya que estamos trabajando con el selector `id` en vez del selector `class`. Agreguemos `width`, `height` y un border solido naranja como referencia para estos 3 `<div>` como sigue:

![Header 2](https://i.imgur.com/mncYgR9.jpg)

![Header 3](https://i.imgur.com/2o93exX.jpg)

 - [ ] Agreguemos ahora el logo de HTML5 usando Font Awesome, ve a https://fontawesome.com/icons y busca el logo de HTML5, cuando lo encuentres, haz click en el logo y copia el codigo indicado en la siguiente imagen, este codigo debe ser pegado en nuestro archivo HTML (dentro del `<div>` del logo):

![Header 4](https://i.imgur.com/Z3ZoqNA.png)

![Header 5](https://i.imgur.com/cmKQR8Z.png)

![Header 6](https://i.imgur.com/mZsVakk.png)

 - [ ] Ahora que tenemos el logo de HTML5, necesitamos agregar los estilos para el mismo. Primero, centra el logo en su `<div>` utilizando flexbox y agregando el siguiente codigo en el selector del logo dentro de nuestro archivo CSS:

![Header 7](https://i.imgur.com/dBUj02y.png)

 - [ ] Cambia el tamano del logo HTML5 agregando el siguiente codigo `fa-2x`, que corresponde a un "literal sizing statement" para iconos de font awesome (para aprender mas sobre los distintos tamanos de los iconos en font awesome, puedes visitar https://fontawesome.com/docs/web/style/size) , dentro de la clase del icono como sigue:

![Header 8](https://i.imgur.com/uHu3aJ5.png)

![Header 9](https://i.imgur.com/PfZKrO8.jpg)

 - [ ] Agrega el texto del username en el `<div>` username (archivo HTML), nota que la palabra `HTML5` esta en negritas, entonces necestias envolver dicho texto en tags `<strong>`. Tambien necesitas un salto de linea `<br>` antes de escribir el texto `Rigoberto`

![Header 10](https://i.imgur.com/xk2p1fM.png)

![Header 11](https://i.imgur.com/cICmzAv.jpg)

 - [ ] Agrega los estilos para alinear el texto del username y cambiar la fuente al estilo Roboto en nuestro archivo CSS como sigue:

![Header 12](https://i.imgur.com/6iXjBJk.png)

![Header 13](https://i.imgur.com/Car9VpN.jpg)

**Nota**: Puedes copiar la fuente Roboto desde [https://fonts.google.com/](https://fonts.google.com/). Ve a las familias seleccionadas y copia el siguiente codigo:

![Header 14](https://i.imgur.com/ozfVhNn.png)

 - [ ] Agrega el icono de los 3 puntos a la derecha de nuestro header utilizando Font Awesome, ve a https://fontawesome.com/icons y busca "ellipsis-vertical", cuando lo encuentres, haz click en el icono deseado y copia el codigo indicado en la siguiente imagen en nuestro archivo HTML (dentro del `<div>` otherOptions), puedes tambien agregar el tamano de una vez (`fa-2x`):

![Header 15](https://i.imgur.com/cbFDU6n.png)

![Header 16](https://i.imgur.com/A8BG0S1.png)

 - [ ] Agrega los estilos en el archivo CSS correspondientes al icono de 3 puntos para moverlo a la esquina derecha de nuestro post y tambien centrarlo como sigue:

![Header 17](https://i.imgur.com/wFPztit.png)

![Header 18](https://i.imgur.com/lAdfesP.jpg)

 - [ ] Remueve los bordes del header y veamos los resultados:

![Header 19](https://i.imgur.com/g2eSZQa.jpg)

 - [ ] Ahora agreguemos la imagen en nuestro `<div>` photo (archivo HTML), puedes agregar cualquier imagen escribiendo el tag `<img>` junto a la fuente de la imagen como sigue:

![Photo 1](https://i.imgur.com/DF6cKsT.png)

![Photo 2](https://i.imgur.com/wEUujXZ.jpg)

 - [ ] Agrega los estilos para encuadrar la imagen en nuestro `<div>` photo en el archivo CSS. Agrega el `width` y `height` a `100%` y agrega el estilo `object-fit:  cover` para que nuestra foto no sea distorcionada al encuadrar la misma:

![Photo 3](https://i.imgur.com/7rkZ3yH.jpg)

  - [ ] Remueve los bordes rojos de nuestra foto y veamos los resultados:

![Photo 4](https://i.imgur.com/zzMHV81.jpg)

 - [ ] Agreguemos ahora los 3 `<div>` contenidos en nuestro footer en donde los "icons", "likes" y "description" seran creados en nuestro archivo HTML como sigue (usemos el selector `id` para estos `<div>`):

![Photo 5](https://i.imgur.com/BEh7s4I.png)

 - [ ] Agrega los estilos en nuestro archivo CSS correspondientes a estos 3 `<div>` usando el selector `#` ya que estamos trabajando con `id` en vez de `class`. Agreguemos `width`, `height` y un borde solido morado como referencia para nuestros 3 `<div>` como sigue:

![Photo 6](https://i.imgur.com/evTy2qP.jpg)

![Photo 7](https://i.imgur.com/CZ8Skb4.jpg)

 - [ ] Ahora agreguemos 4  `<div>`  en nuestro archivo HTML de acuerdo a la estrategia vista en el GIF (asegurate de agregar estos 4 `<div>` dentro del `<div>` icons), estos `<div>` contendran los iconos de "heart", "comment", "send" y "save", usemos de nuevo el selector `id`  para estos 4 `<div>`:

![Icon 1](https://i.imgur.com/4PdnJXY.png)

 - [ ] Agreguemos ahora los iconos usando Font Awesome, ve a [https://fontawesome.com/icons](https://fontawesome.com/icons) y busca "heart" para el icono de corazon, "comment" para el icono de comentario, "paper-plane" para el icono de enviar y "bookmark" para el icono de guardar, copia los codigas de los iconos y pegalos en los `<div>` correspondientes, agreguemos tambien el tamano de dichos iconos, utilizemos el tamano `fa-2xl` para esta ocasion:

![Icon 2](https://i.imgur.com/6CzCbt3.png)

 - [ ] Agrega los siguientes estilos en nuestro archivo CSS para asi dibujar los recuadros naranjas para tener nuestra referencia de la posicion de nuestro iconos:

![Icon 3](https://i.imgur.com/ezF0dZZ.jpg)

![Icon 4](https://i.imgur.com/iJ4UQXN.jpg)

 - [ ] Ahora tenemos que hacer que nuestro recuadros naranjas sean `display: flex` y alinear los items vertical y horizontalmente. Nota que, para el icono de guardar o "save", tendremos que cambiar el `flex-direction` a `column` para que podamos aplicar el `flex-end` y colocar el icono de guardar en el lado derecho de esta seccion. Aplica los siguientes estilos en el archivo CSS:
 
![Icon 5](https://i.imgur.com/KjMAZAC.jpg)

![Icon 6](https://i.imgur.com/jbD8ETF.jpg)

 - [ ] Remueve los recuadros naranjas y morados (seccion de iconos) de los estilos en el archivo CSS y veamos los reasultados:

![Text 1](https://i.imgur.com/T2CIyfS.jpg)

 - [ ] Ahora para la parte final, agreguemos el texto en el archivo HTML que corresponde a la seccion de "likes" y "description", recuerda utilizar el tag `<strong>` cuando sea necesario (negritas). Puedes tambien escribir la palabra `lorem` + enter en la seccion de "decription" para hacer un llenado automatico de texto:

![Text 2](https://i.imgur.com/MeXk4PI.png)

![Text 3](https://i.imgur.com/dMtIpUQ.jpg)

 - [ ] Ahora solo tenemos que agregar los estilos correspondientes a las secciones de "likes" y "description" en nuestro archivo CSS. Agrega la fuente Roboto, agrega algo de padding a estas secciones, remueve los recuadros de referencia faltantes y habremos finalizado el post:

![Text 4](https://i.imgur.com/bylcc3i.jpg)

![Text 5](https://i.imgur.com/d8Bkuh2.jpg)

## ¿Qué hacer si estás atascado?

Pregúntale al instructor o a tus compañeros de clase de inmediato, no te quedes estancado por más de 15 minutos, porque este es uno de tus primeros ejercicios y no se espera que sepas todo. ¡¡¡Haz preguntas!!!

## Fundamentos:

Este ejercicio cubre los siguientes fundamentos:

1. Estructura básica para cada sitio web HTML5.  
2. La etiqueta *Link* para importar Reglas CSS.  
3. Utilizando fuentes de google.  
3. Usando los diferentes selectores disponibles en CSS.  
4. Trabajo con cajas: borde, relleno y márgenes.  
5. Overflow.  
6. Usando Flex vs Position vs Float vs Display.  
7. Usando un formulario simple.  
