# READ 05
## Diseño de paginas web con CSS
1. **¿Cuál es el propósito de CSS?**

    _El propisto es darle estilo a nuestra pagina web._

2. **¿Cuáles son las tres formas de insertar CSS en tu proyecto?**

    _Las tres formas de insertar es:_
     + CSS externo: Se crea un archivo "mystyle.css", que luego se define dentro de la página HTML

           body {
            background-color: lightblue;
            }

            h1 {
            color: navy;
            margin-left: 20px;
            }

     + CSS interno: Se define dentro de la pagina principal, usando el comando <style>

             <!DOCTYPE html>
                <html>
                <head>
                <style>
                body {background-color: linen;}
                h1 {color: maroon;}
                </style>
                </head>

                <body>
                <h1>ENCABEZADO COLOR MARRON</h1>
                <h1>ENCABEZADO COLOR MARRON</h1>
                </body>
                </html>

     + CSS en línea: Cuando se quiere aplicar un estilo unico a un solo elemento.

            <!DOCTYPE html>
            <html>
            <body>
            <h1 style="color:red">EL PRIMER ENCABEZADO ROJO</h1>
            </body>
            </html>

3. **Escribe un ejemplo de una regla CSS que daría texto rojo a todos los elementos <p>**

    _Esto seria insertando un CSS externo_

                <!DOCTYPE html>
                <html>
                <head>
                <link rel="stylesheet" href="mystyle.css">
                </head>
                <body>
                <p>QUIERO SER COLOR ROJO</P>
                <p>QUIERO SER COLOR ROJO</P>
                <p>QUIERO SER COLOR ROJO</P>
                </body>
                </html>

    _**Para ello crearemos el archivo mystyle.css_**

            p {
                color: red;
              }
