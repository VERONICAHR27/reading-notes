# DEBATE 03
## React: Funciones como Props

1. **Comunicación de datos vs. comunicación de eventos**
    
    _¿En qué se diferencian las props que envían datos estáticos de las funciones como props que envían eventos o decisiones?_

2. **Responsabilidad y flujo de control:**

    _Si un componente padre le pasa una función al hijo para que la use cuando el usuario haga clic, ¿quién realmente tiene el control de lo que pasa al final? ¿El padre o el hijo?_

3. **Estado centralizado vs. estado local:**

    _Considera cuándo es mejor manejar el estado directamente en el hijo y cuándo conviene centralizarlo en el padre. ¿Cómo afecta esto la escalabilidad y el mantenimiento del código?

_

4. **Funciones anónimas y de flecha:**

    _En muchos ejemplos de React, se usan funciones de flecha directamente dentro de un onClick o al pasar funciones como props. ¿Qué implicaciones tiene esto en términos de performance y re-renderizado? ¿Es siempre la mejor práctica o hay situaciones donde debería evitarse_

5. **Delegación de responsabilidades:**

    _Imagina un componente hijo que necesita validar datos antes de llamar a la función del padre. ¿Dónde debería ocurrir esa validación: en el hijo o en el padre?_

6. **Escalabilidad y legibilidad:**

    _Si un componente padre pasa múltiples funciones como props a un componente hijo (seleccionar, eliminar, actualizar, etc.), ¿cómo afecta esto la legibilidad y mantenibilidad del código?_


*Si hay mitos o verdades por reconocer, coloca todos los enunciados listados y un indicador para diferenciarlos según tu analisis (M: mito, V: verdad, I: intermedio).

**Si hay preguntas por responder, coloca cada pregunta y luego la respuesta a la que llegaste.