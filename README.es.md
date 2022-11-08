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

<p  align="center"><img  src="https://github.com/breatheco-de/exercise-instagram-post/blob/master/preview.png?raw=true"  height="300" /></p>

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

![Container](https://i.imgur.com/UCT8efS.jpg)

 - [ ] Como vemos en el GIF, el color de fondo de nuestro website es negro, por ende nuestro contenedor necesita cubrir todo nuestro website, para hacer esto, necesitamos ir a nuestro archivo CSS y agregar un `margin: 0` a nuestro body completo usando el `*` como selector

![Container 2](https://i.imgur.com/C8X3gNe.jpg)

 - [ ] Luego tenemos que agregar los estilos a nuestro container, agregando el background color, el ancho "width" y altura "height" para cubrir todo nuestro website

![Container 3](https://i.imgur.com/6yTO2a0.jpg)

Ahora, como vemos en el GIF, tenemos un post `<div>` (el verde) que contiene 3 `<div>` principales (los rojos), que son el header, photo y el footer.

 - [ ] Agrega el `<div>` post (el verde en el GIF) y los 3 principales `<div>` (los rojos en el GIF) contenidos en la publicación `<div>` en el archivo HTML de la siguiente manera:

![Main Divs](https://i.imgur.com/TkSqQRx.jpg)

- [ ] Agregue los estilos necesarios en el archivo CSS para hacer que el `<div>` post sea un rectángulo blanco centrado de la siguiente manera:

**TIP: Tratar de usar flexbox en este ejercicio**

![Post 2](https://i.imgur.com/o3VCPsL.jpg)

 - [ ] Agrega los 3 `<div>` en nuestro archivo HTML de acuerdo con el GIF (asegúrate de agregarlos dentro de nuestro `<div>` header), que contendrá el logo HTML, el título/nombre de usuario de la foto y el icono de 3 puntos , usemos `id` como selector para estos 3 `<div>`. Para ayudarnos en este proceso, podemos agregar un borde sólido rojo de 1px para ayudarnos a visualizar cómo se distribuyen los `<div>` en nuestro post de la siguiente manera:

![Header 1](https://i.imgur.com/ng5lrcW.jpg)

![Main Divs 3](https://i.imgur.com/YepRjDf.jpg)


 - [ ] Agrega la información correspondiente (logo HTML, título de la publicación e ícono de 3 puntos) en el `<div>` correcto en nuestro archivo HTML, así como los estilos correspondientes en nuestro archivo CSS para terminar el header el cual debera verse de la siguiente manera:
 
![Header 19](https://i.imgur.com/g2eSZQa.jpg)

**TIP: Sigue los siguientes pasos para usar los iconos de Fontawesome:**

 - Ve a https://fontawesome.com/icons y busca el logo deseado, una vez que lo hayas encontrado, haz clic en el logo y copia el siguiente código en nuestro archivo HTML (dentro del `<div>` logo):

![Header 4](https://i.imgur.com/Z3ZoqNA.png)
![Header 5](https://i.imgur.com/cmKQR8Z.png)


 - Puedes cambiar el tamaño del ícono de Fontawesome agregando este código `fa-2x`, que corresponde a una declaración de tamaño literal para los íconos de Fontawesome (para obtener más información sobre el tamaño de los íconos de Fontawesome, puedes visitar https://fontawesome.com/docs/web/style/size), agrega este codigo en la clase del icono de la siguiente manera:

![Header 8](https://i.imgur.com/uHu3aJ5.png)

 - Aquí hay otro ejemplo usando el ícono de 3 puntos:

![Header 15](https://i.imgur.com/cbFDU6n.png)

 - [ ] Ahora agreguemos la imagen a nuestro `<div>` photo (archivo HTML), puedes agregar cualquier imagen escribiendo la etiqueta `<img>` junto a la fuente de la imagen de la siguiente manera:

![Photo 1](https://i.imgur.com/DF6cKsT.png)

![Photo 2](https://i.imgur.com/wEUujXZ.jpg)

 - [ ] Agrega los estilos en nuestro archivo CSS para que se ajuste la imagen en nuestro `<div>` photo, se debe de ver de la siguiente manera:

![Photo 4](https://i.imgur.com/zzMHV81.jpg)

 - [ ] Agreguemos los 3 `<div>` contenidos en nuestro footer en donde los "icons", "likes" y "description" (los rectángulos morados en el GIF) estarán en nuestro archivo HTML de la siguiente manera (utilicemos el selector de ID nuevamente para estos `<div>`):

![Photo 5](https://i.imgur.com/BEh7s4I.png)

![Photo 7](https://i.imgur.com/CZ8Skb4.jpg)

 - [ ] Ahora agreguemos los 4 `<div>` en nuestro archivo HTML de acuerdo con el GIF (asegúrate de agregarlos dentro de nuestro `<div>` icons), que contendrá los íconos de "heart", "comment", "send" y "save", usemos `id` como selector para estos 4 `<div>`:

![Icon 1](https://i.imgur.com/4PdnJXY.png)

 - [ ] Agreguemos los íconos usando Font Awesome, ve a [https://fontawesome.com/icons](https://fontawesome.com/icons) y busca "heart" para el ícono de corazón, "comment" para el ícono de comentario, "paper-plane" para el ícono de enviar y "bookmark" para el ícono de guardar, copia los códigos de los íconos y pégalos en sus `<div>` correspondientes, agreguemos también el tamaño, usa `fa-2xl` para esta ocasión:

![Icon 2](https://i.imgur.com/6CzCbt3.png)

 - [ ] Agrega los estilos correspondientes a estos íconos en nuestro archivo CSS. Los íconos deberían verse así:

![Text 1](https://i.imgur.com/T2CIyfS.jpg)

 - [ ] Ahora, para la parte final, agreguemos el texto en nuestro archivo HTML correspondiente a las secciones de "likes" y "description", recuerda usar la etiqueta `<strong>` siempre que sea necesario. También puedes escribir `lorem` + enter en la sección de descripción para autocompletar ese texto:

![Text 2](https://i.imgur.com/MeXk4PI.png)

![Text 3](https://i.imgur.com/dMtIpUQ.jpg)

 - [ ] Solo necesitamos agregar los estilos en nuestro archivo CSS correspondientes a la sección "likes" y "description". Agrega la fuente tipo Roboto, agrega algo de padding, elimina los cuadros guias restantes y el post deberia estar listo luciendo de la siguiente manera:

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
