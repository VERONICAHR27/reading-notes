# Read 03: Lecturas: Listas en HTML, Control de flujo en JS, y CSS: Box Model
***Los temas tratados en la lectura numero 3 nos permiten tener una mejor navegacion en las paginas wek y nos ayuda para tener conocimientos previos a la clase 3 que se va a desarrollar, la cual si tenemos dudas lo podamos resolver en clase***

## **HTML**
1. **¿Cuándo se puede utilizar una lista no ordenada en tu documento HTML?**

    _Las listas no ordenadas se pueden usar cuando cuando el orden de lo que se ubica no tenga un significado, por ejemplo cuando quieres listar las cosas que te gustan, las dificultades que presentas, entre otras que no tenga significado el orden en la que las ubicas._
2. **¿Cómo cambias el estilo bullet de la lista de elementos no ordenados?**

     _Se debe utiliza la propiedad de estilos de css_   
     
            list-style-type

3. **¿Cuándo debes usar una lista ordenada o lista no ordenada en tu documento HTML?**

    _Se debe usar una lista ordenada cuando el oreden en las que los ubica tenga un significado, como por ejemplo en las recetas. Y por otro lado se utiliza una lista no ordenada cuando el orden no importa.

4. **Describe dos formas en las que puedes cambiar los números en los elementos de la lista proporcionados por una lista ordenada**

        <ol start="5">
        <ol type="I">

## Aprende CSS**
1. **Describe las propiedades de margin y padding en CSS como si fueran los personajes de una historia. ¿Cuál es su rol en la historia: “El Box Model”?**

+ El padding cumple la funcion de poder definir el espacio que se deja alrededor del contenido.
+ El margin cumple la funcion de definir el espacio que se deja entre la capa y otro elemneto.
2. **Enumera y describe las cuatro partes de un box del elementos HTML según el box model.**

    _Las cuatro partes de un box es: 
    + Contenido de la caja: Se encuentra el contenido 
    + Relleno de la caja: Espacio entre el contenido y borde del elemento
    + Borde de la caja: Se encuentra alrededor del padding y el contenido
    +  Margen de la caja: Espacio entre la caja y otros elementos.
## **Aprende JS**
1. **¿Qué tipos de datos puedes almacenar en un Array?**

    _Se puede almacenar cualquier elemento en un array y tambie dentro de un array se puede agregar otro array, a continuacion se muestra algunos datos que se puede almacenar._
    + Cadena
    + numero
    + objeto
2. **¿El array people es un array de JavaScript válido? De ser así, ¿cómo puedo acceder a los valores almacenados? Y si no, ¿por qué?**

            const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant','fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
    _Si es un array valido y para acceder a los valores debemo encadenarlo dos pares de corchetes.
3. **Enumera cinco opreadores abreviados de asignación en javascript y describe lo que hacen.**
    + ASIGNACION DE ADICION: X +=Y: Suma el valor de Y al valor de X para luego almacenr el resultado en X
    + ASIGNACION DE RESTA: X -=Y: Resta el valor de Y al valor de X para luego almacenr el resultado en X
    + ASIGNACION DE MULTIPLICACION: X *=Y: Multiplica el valor de Y al valor de X para luego almacenr el resultado en X
    + ASIGNACION DE DIVISION: X /=Y: Divide el valor de Y al valor de X para luego almacenr el resultado en X
    + ASIGNACION: X=Y: El valor de x es asignado a y.
4. **Lee el código a continuación, evalúa la últimaexpresión y explica cuál sería el resultado y por qué.**

            let a = 10;
            let b = 'dog';
            let c = false;
            (a + c) + b;
    _El resultado seria 10dog, por que el false se va a convertir en un 0 al aplicar la operacion aritmetica_

5. **Describe un ejemplo cotidiano de por qué una declaración condicional se debería usar en un programa en JavaScript**

     _Se deberia usar por que se necesita tomar decisiones, por ejemplo en un campeonato de tenis el jugador tiene 3 intentos, si al fallar los tres intentos ya queda descalificado._

6. **Da un ejempo de por qué un Bucle es últil en JavaScript.**

    _El bucle es util ya que permite repetir algo que se desea hacer las veces que se solicita, es decir queremos hacer 20 iteraciones repetitivas, sin el bucle estarimos repitiendo el mismo codigo 20 veces para que nos muestre las iteraciones solicitadas_