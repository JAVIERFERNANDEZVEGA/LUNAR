# LUNAR
## EL CÓDIGO HTML 
1. Dentro de la etiqueta head  añadiremos las etiquetas *title* (para el nombre de la pestaña), meta (para añadir los metadatos name y content) y por último la etiqueta link (para añadir la dirección de nuestro archivo.css de estilo)
  
2. BODY:
 * 2.1 con la etiqueta img introducimos la imagen de la nave espacial y el planeta tierra guardado en la carpeta img , también le añadiremos a cada etiqueta img el atributo id para poder usar el selector id en CSS y manipular las distintas etiquetas img de forma individual.
 * 2.2 Con la etiqueta div añadiremos los dos paneles uno para CONTROL PANEL  y otro para GAME OPTIONS también añadiremos a la etiqueta div el atributo id para identificar las etiquetas div de manera individual y añadir estilo CSS correspondiente. Dentro de cada etiqueta div añadiremos el titulo del panel con etiqueta h1 y las opciones con etiqueta p, por último a las etiquetas h1 le añadiremos el atributo class con el mismo nombre para poder usar el selector CSS y añadir el mismo estilo de titulo a los dos paneles.

## EL CÓDIGO CSS

1. Usaremos el selector body con las declaraciones( background-image,background-repeat,background-position,background-attachment,background-color) para añadir la imagen del suelo de la luna debajo de la pantalla web y repetir la imagen en sentido horizontal para simular un suelo uniforme de la luna en toda la pantalla,  el fondo de imagen negro para simular el espacio.
2. .#tierra y #nave: Usaremos los selectores CSS de id para los id de las etiquetas img de planeta tierra y nave espacial con las declaraciones (width,height,position,left,top) para configurar el tamaño de las imágenes y su posición en la pantalla del navegador web.
3. .#controlpanel y #gameoptions: Usaremos los selectores CSS de id para los id de las etiquetas div de CONTROL PANEL y GAME OPTIONS  con las declaraciones (background-color,border,padding,width,position,top,left) para configurar el fondo, tamaño, bordes y posición de la etiquetas  div.
4. .titulos: Usaremos el selector CSS de clase para configurar los títulos h1 de las etiquetas div  de los paneles Game option y Control panel con las declaraciones (background-color,color,text-align,margin) para añadir fondo negro con letras blancas, texto centrado y margen 0 para ajustar bien el espacio superior del título dentro del recuadro de la etiqueta div.
