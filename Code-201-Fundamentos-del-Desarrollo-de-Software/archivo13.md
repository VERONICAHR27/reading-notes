# Read 13:  Introducción a la Persistencia con Local Storage
***Con la lectura 13 se aprendio a como realizar un almacenamiento local para luego ser utilizado en diversos sitios web***

## **Local Storage and How To Use It On Websites**
1. **¿Por qué un desarrollador utilizaría el local storage para una aplicación web?**

    _El desarrollador utiliza el local storage como estrategia, debido a que el HTTP no tiene un estado y esto hace que cuando estas en una aplicacion y lo cierras los datos ingresados se pierden a diferencia cuando lo haces en el escritorio que cuando cierras la aplicacion qe usas al volver abrir se restaura al estado mas reciente._ 

2. **¿Qué información no se puede guardar en el local storage?**

    _Solo se puede guardar string_

3. **¿Qué tipo de datos se pueden guardar en el local storage? ¿Cómo puedes convertirlo a ese tipo de archivo antes de guardarlo?**

    _En el local storage solo se pueden guardar el tipo de dato "STRING", que es una cadena de texto._
    _Para poder convertirlo cualquier tipo de dato aun JSON string se utiliza 'JSON.stringify' y de esta manera permite guardar la informacion en el localStorage. A continuacion se muestra un ejemplo:_

        
        const user ={
            name: "vero",
            lastName: "Hilario",
            age: 25
        }    
            localStorage.setItem('datos',JSON.stringify(user));

## **“The Past, Present, and Future of Local Storage for Web Applications”**
_El almacenamiento local tienen una ventaja sobre las aplicaciones web. Las cookies  se puede utilizar para  el almacenamiento local para pequeñas cantidades de datos, pero tiene algunas deventajas como:
+ Relentiza la aplicacion web.
+ Envia datos sin cifrar a traves de internet.
+ Esta limitado para 4KB de datos

