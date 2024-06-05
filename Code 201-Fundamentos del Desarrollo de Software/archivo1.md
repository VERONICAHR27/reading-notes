# Read 02:Conceptos básicos de HTML, CSS y JS

## Los temas tratados en la lectura numero 2 son fundamentales para poder estructurar de forma correcta las paginas que diseñamos, ademas de aplicar los estilos de forma adecuada.

A. **HTML**
    1. **¿Por qué es importante utilizar elementos semánticos en nuestro HTML?**

        _Es importante ya que nos permite estructurar el texto y de esta manera el contenido que se presente muestra el significado que se quiere dar a conocer y a la vez es mas amigable con el usuario_

    2. **¿Cuántos niveles de encabezado existen en HTML?**

        _Los encabezados en htm son 6:_
           + <h1></h1>
           + <h2></h2>
           + <h3></h3>
           + <h4></h4>
           + <h5></h5>
           + <h6></h6>

    3. **¿Cuáles son algunos de los usos para los elementos <sup> y <sub>?**

          + Los elemento <sup> y <sub> que son superindice y subindice se usan para:
          + Establecer fechas
          + Formulas matematicas
          + Ecuaciones
          + Formulas Quimica

    4. **Al utilizar el elemento <abbr>, qué atributo se debe añadir para proporcionar una ampliación del término?**

        _El atributo que se debe agregar es "title", esto permite sabes sobre el termino que se va a tratae._

Aprende CSS
¿De qué formas podemos añadir CSS a nuestro HTML?
Existe tres metodos para añadir css, pero la mas recomendable es la hoja de estilo externa.
Hoja de estilo externa: Par esto se crea una hoja de estilo independiente y luego se vincua con la pagina. 
Hoja de estilo interna: Para ello dentro de la pagina y dentro del elemento <head> se coloca el CSS mediante el elemento <style>
Estilo en linea: Esto se declara para que solo a un elemento especifico se coloque estilos.

¿Por qué deberíamos evitar utilizar estilos inline?
Se debe evitar de usar porque en muchas ocasiones si tienes que hacer cambios, tendriamos que hacer a cada uno la cual toma tiempo. }
Por otro lado, al utilizar este codigo se dificulta comprender el codigo.

Revisa el código a continuación y responde a las siguientes preguntas:
¿Qué representa el selector?
El selector es un elemento de html la cual indica que los estilos que se agregue a este selector debe aplicarse. En este ejemplo tenemos un selsctor h2 
¿Qué componentes son declaraciones CSS?
Las propiedades y los valares, como el ejemplo:
color en una propiedad y black es el valor que se asigna.
¿Qué componentes se consideran propiedades?
 color: black;
 padding: 5px;

Aprende JS
¿Qué tipo de dato es una secuencia de texto entre comillas simples?
El tipo de dato es el STRING

Enumera 4 tipos de operadores en JavaScript
SUMA: Su simbolo es +
ASIGNACION: Su simbolo es =
IGUALDAD: Su simbolo es ===
DIVISION: Su simbolo es /

Describe un problema práctico que puedes resolver con una función.

function suma(numer01, numero2){
let resultado = numero1 + numero2
return resultado;
}

Tomando decisiones en tu código — condicionales.

Si una declaración if comprueba una codicion y si resulta verdadera, entonces el código se ejecutará.

¿Cuál es el uso del else if?
Se usa para especificar una nueva condicion para probar si la primera condicion retorne falso.

Enumera 3 tipos de operadores de comparación.
Igualdad: ===
Menor que: <
Mayor que >

¿Cuál es la diferencia entre los operadores lógicos && y ||?
La diferencia es que el operadore lógicos && para que retorne verdadero todas las expresiones deben ser verdaderas.
Mientras que el operados logico || para que retorne verdadero algunas expresiones deben deben ser verdaderas.


