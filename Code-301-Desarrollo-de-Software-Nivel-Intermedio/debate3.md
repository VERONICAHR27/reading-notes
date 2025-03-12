# DEBATE 03
## React: Funciones como Props

1. **Comunicación de datos vs. comunicación de eventos**
    
    _¿En qué se diferencian las props que envían datos estáticos de las funciones como props que envían eventos o decisiones?_

    + Los props estáticas son útiles para pasar datos que no cambian y que el componente hijo solo necesita para visualización o cálculos(v)
    + Los props de funciones son útiles cuando se necesita permitir que el componente hijo interactúe con el padre, normalmente mediante el manejo de eventos, la toma de decisiones o la actualización del estado.(v)
    
2. **Responsabilidad y flujo de control:**

    _Si un componente padre le pasa una función al hijo para que la use cuando el usuario haga clic, ¿quién realmente tiene el control de lo que pasa al final? ¿El padre o el hijo?_

    El hijo tiene el control de invocar la función en respuesta a un evento y el padre mantiene el control sobre lo que realmente ocurre cuando la función se ejecuta.(v)
    Es decir, el padre define el comportamiento y las decisiones, mientras que el hijo solo invoca ese comportamiento.(v)

3. **Estado centralizado vs. estado local:**

    _Considera cuándo es mejor manejar el estado directamente en el hijo y cuándo conviene centralizarlo en el padre. ¿Cómo afecta esto la escalabilidad y el mantenimiento del código?

    Cuando el estado necesita ser compartido entre varios componentes conviene centralizarlo en el padre porque simplifica la gestión del estado y evita la duplicación de lógica. Pero si el estado solo afecta al comportamiento o la UI de un solo componente y no necesita ser compartido con otros, es más sencillo manejarlo en el hijo.(v)

4. **Funciones anónimas y de flecha:**

    _En muchos ejemplos de React, se usan funciones de flecha directamente dentro de un onClick o al pasar funciones como props. ¿Qué implicaciones tiene esto en términos de performance y re-renderizado? ¿Es siempre la mejor práctica o hay situaciones donde debería evitarse_

    Función de flecha en onClick o como prop: Es conveniente, pero puede afectar el rendimiento si se utiliza incorrectamente, ya que crea nuevas instancias de funciones en cada renderizado.(v)

    Impacto en el rendimiento: Usar funciones de flecha sin tener en cuenta el rendimiento puede provocar re-renderizados innecesarios en componentes hijos y disminuir la eficiencia de la aplicación.(v)

    Mejor práctica: Para componentes simples o pequeños, el uso de funciones de flecha no es un problema significativo.(v)


5. **Delegación de responsabilidades:**

    _Imagina un componente hijo que necesita validar datos antes de llamar a la función del padre. ¿Dónde debería ocurrir esa validación: en el hijo o en el padre?_
    
    Validación en el hijo: Es apropiada cuando la validación es local, simple, y específica de ese componente, también es útil para dar retroalimentación inmediata al usuario.(v)

    Validación en el padre: Es mejor cuando la validación depende de un contexto más amplio o de un estado global, o cuando múltiples hijos necesitan ser validados de manera consistente bajo las mismas reglas.(v)

6. **Escalabilidad y legibilidad:**

    _Si un componente padre pasa múltiples funciones como props a un componente hijo (seleccionar, eliminar, actualizar, etc.), ¿cómo afecta esto la legibilidad y mantenibilidad del código?_

    Legibilidad: Pasar muchas funciones como props puede hacer que el código se vuelva difícil de leer y entender, especialmente si las funciones son similares o no están bien documentadas.(v)

    Mantenibilidad: El mantenimiento se complica cuando se tienen muchas funciones interrelacionadas, ya que cualquier cambio en la lógica del padre puede tener efectos secundarios en muchos componentes hijos.(v)
    
    Escalabilidad: A medida que la aplicación crece, el prop drilling y la alta dependencia entre componentes pueden hacer que escalar el código sea más difícil.(v)