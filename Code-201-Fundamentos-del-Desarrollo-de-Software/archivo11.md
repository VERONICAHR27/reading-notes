# Read 11:  Audio, video, imágenes
***Los temas tratados en la lectura numero 11 nos permite insertar audios y videos a nuestra pagina web, teniendo en cuenta cada una de las propiedades, estilos a aplicar.***

## **Contenido de audio y video**
1. **Explica cómo la capacidad de utilizar video y audio en la web ha ido evolucionando desde el comienzo de los 2000.**

    _Cuando se tuvo banda de ancho suficiente se empezo a usar audio y video en la web, ya que al inicio en las web nativas no se podian insertar, al incio tenia ciertos problemas como las caracteristicas, seguridad y accesiilidad, pero al pasar los años esto fue mejorando e implementandose de forma correcta._ 

2. **Describe el uso de los atributos src y controls en el elemento video.**
    + src: Contiene la ruta del video que se quiere mostrar, la ruta puede ser de forma remota o local.
    + controls: Permite controlar la reproducion de los videos.

3. **¿Por qué es importante tener contenido de respaldo en el elemento <video>?**

    _Es importante ya que no todos los equipos no pueden soportar el video que se suba, esto mayormente se puede dar en equipos antiguos._

4. **Escribe una historia corta en donde <audio> y <video> son personajes.**

    _En un salon de clases la maestra trata sobre el tema de la guerra mundial y para muchos estudiantes esto se les complica entender por que la maestra solo lee y cuenta lo que sucedio, sin embargo al darse cuenta que no captaba la atencion de los niños decidio utilizar dos elementos fundamentales como imagenes y videos, mediante ello los estudiantes puedieron entender mejor como sucedio la segunda guerra mundial._

5. **¿En qué se diferencia el layout Grid del Flex?**

    _El grid esta diseñado en cuadricula bidimensional y el flex tiene un flujo unidireccional._

6. **Grid container, grid item, y grid line son algunos de los términos importantes que se deben entender al utilizar Grid. Por favor describe estos términos en unas pocas frases.**
    + GRID CONTAINER: Es el elemento padre, se encarga de manejar las filas y columnas que se encuentran dentro.
    + GRID ITEM: Son los hijos descendientes del contenedor.
    + GRID LINE: Forman las lineas divisoras y pueden ser verticales y horizontales.

## **Imágenes Responsivas**
1. **Además de hacer que un sitio se vea atractivo visualmente en diferentes tamaños de pantalla, ¿por qué los desarrolladores deberían hacer imágenes responsivas?**

    _Porque esto permite mejorar el rendimiento en diferentes dispositivos y permite el cambio de resolucion para que se adapte a las caracteristicas de los distintos disposiivos._

2. **Define los siguientes atributos de <img>: srcset y sizes. Escribe un ejemplo de cómo se usan.**


        <img
            srcset="
                imagen1.jpg 320w,
                imagen2.jpg 480w,
                imagen3.jpg 800w
            "
            sizes="(max-width: 320px) 280px,
                        (max-width: 480px) 440px,
                        800px"
        src="imagen3.jpg"
        alt="Ejemplo de elementos del img" />

    + srset: Esto define el conjunto de imagenes que el navegador podra elegir y el tamaño de cada uno.

    + sizes: Esto define el conjunto de condiciones y tamaño de las imagenes.
  
3. **¿Cómo es que srcset es más útil para las imágenes responsivas que CSS o JavaScript?**

    _Por que permite elegir al navegador la imagen a mostrar y el tamaño, que se adapte al dispositivo a utilizar._
     
## **Imágenes en HTML - Otras Tecnologías de Incrustación**
_Las imagenes en una pagina web son importantes para que sea mas atractivo para el usuario, en esta lectura nos enseña de como insertar las imagenes a la pagina web y ponerle estilos a cada uno de ellas._

        <img
        src="images/ejemplo.jpg"
        alt="ejemplo de como insertar una imagen"/>