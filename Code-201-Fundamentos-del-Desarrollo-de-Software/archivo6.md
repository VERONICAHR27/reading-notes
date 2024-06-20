# Read 06: 
***Los temas tratados en la lectura numero 6 nos permiten tener conocimiento del nuevo tema de objetos en javaScript y de esta manera tenemos nocion de como funciona los objetos. Esto nos ayuda  a tener conocimientos previos a la clase 6 que se va a desarrollar***
## **Conceptos básicos de los objetos JavaScript**
1. **¿Cómo le describirías un objeto a un amigo sin conocimiento técnico con el que creciste?**

    _Un objeto es la recoleccion de datos, es decir un ejemplo una pelota es un objeto, ya que tiene propiedades como el color, diseño, tamaño, entre otros._

2. **¿Cuáles son algunas de las ventajas de crear objetos literales?**
    + Declara  sus propiedades de manera explicita.
    + Agrupan la informacion de la propiedad de manera textual.
    + Transfiere una serie de elementos de datos relacionados y estructurados
3. **¿En qué se diferencian los objetos de los arrays?**

    _Se diferencian en que los array se utiliza el numero de indice para seleccionar un elemento, y en los objetos se utiliza el nombre que esta asociado con el valor de cada miembro._

4. **Da un ejemplo acerca de los momentos en los que necesitarías utilizar bracket notation para acceder a la propiedad de un objeto en vez de dot notation.**

    _Se utilizario la notacion punto cuando se conoce la propiedad, en cambio con la notacion bracket es util cuando se desea acceder de forma dinamica a una propiedad._

5. **Evalúa el siguiente código. ¿A qué se refiere el término this y cuál es la ventaja de utilizarlo?**

            const dog = {
                name: 'Spot',
                age: 2,
                color: 'white with black spots',
                humanAge: function (){
                    console.log(`${this.name} is ${this.age*7} in human years`);
                }
            }

    _El termino this hace referencia al objeto actual en el que se escribe el codigo, esto es importante usar cuando se generan objetos dinamicos.  _

## **Introducción al DOM**
1. **¿Qué es el DOM?**

    _El dom  es el modelo de objeto del documento, la cual permite ver la repreesentacion estructurada de nuestro documento._

2. **Describe brevemente la relación entre el DOM y JavaScript.**

    _La relacion que tienen es que el Dom permite que javaScript pueda llegar, crear, remplazar, hacer cambios en los elementos que tiene nuestra pagina._

## **Marcadores y Repaso**
1. **¿Por qué parece tan difícil programar?**

    _Esto se da por que muchas veces solo nos centramos en el codigo, sin antes analizar el tema que se desea trabajar, para ello s debe tener en cuenta 4 pasos para que se nos resulte facil_

    + Analizar el problema
    + Diseñar un metodo de solucion.
    + Escribir el problema en un lenguaje de programacion.
    + Realizar pruebas de lo que se plateo.


