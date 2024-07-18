# Read 14:
***Los temas tratados en la lectura numero 14 nos permite insertar algunos estilos para que nuestra pagina que diseñamos sea mas interactivo con el usuario***

## **CSS Transforms**
1. **¿Qué le permite al desarrollador hacer un CSS transform a un elemento?**

    _Con el elemento transform se puede posicionar, modificar los elementos para bidimensional y para tridimensional. Cada uno de esto tiene sus propias propiedades y valores individuales. La desventaja de usar este elemento es que no es tan compatible con todos los navegadores, algunas de las funciones a utilizar son:_

             transform: matrix(1, 2, 3, 4, 5, 6);
             transform: translate(120px, 50%);
             transform: skew(30deg, 20deg);
             transform: scale(2, 0.5);

2. **Da un ejemplo de un transform y cómo puedes utiliarlo en un página web.**

    _A continuacion se mostrara un ejemplo de como centrar vertical y horizontal una imagen, esto se utiliza en las paginas web cuando deseas que las imagenes insertadas esten centradas._


        div {
            height: 300px;
            background-color: #EEE;
            position: relative;
        }
        div img{
            position: absolute;
            left: 50%;
            top: 50%;
            transform: translate(-50%, -50%);
            -webkit-transform: translate(-50%, -50%);
        }

## **Transiciones CSS Animaciones CSS**
1. **¿Qué le permite al desarrollador hacer un CSS transition a un elemento?**

    _Permite aplicar diversos cambios de estilo gradual a los elementos del documento HTML, y tambien te permite especificar el tiempo que se va a producir la transformacion estre los estilos que se aplica. La sintaxis de esto es:_

        transition:[propiedad a modificar] [Duración] [Tipo de animación] [Retardo];

        .caja1{
            background-color: #C0392B;
            transition: background-color 1s linear;
        }
        .caja1:hover{
            background-color: #3F51B5;
        }      

2. **¿En qué se diferencia un CSS animation de un CSS transition?**

    _CSS TRANSITION permite crear una transicion suave y solo se mueve de un estado a otro es decir solo puede ir de A a un estado B, el CSS ANIMATION es mas flexible y tiene mas estados._

## **8 simple CSS3 transitions that will wow your users**
1. **¿Cuáles son los beneficios de utilizar CSS transitions en páginas web?**

    _Los beneficios es que que los usuarios seran mas interactivos con la pagina, y hasta se puede lograr contener conversacions con los usuarios, ademas de ello utilizar css transitions es facil, flexible para su implemenentacion.  

2. **¿Cómo este tema encaja con tus metas a largo plazo?**

      _A travez de poder aplicar cada uno de ellos haremos que nuestras paginas que implementemos tengan mayor audiencia y nos generen beneficios para lo que esta prpuesta la pagina._
     
## **Pure CSS Bounce Animation - 6 Buttons animated - CSS3 Animations: Keyframes**
 _En cada uno de estos apartados nos muestran diversos juegos para poder aplicar lo aprendido, ademas de ello al desarrollar cada uno de estos juegos nos ayuda a reforzar algunos temas que no estaba claro y asi tener un mejor dominio de todo._