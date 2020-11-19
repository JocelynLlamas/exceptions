1. Clonar repositorio https://github.com/iuresti/exceptions-1
2. Ejecutar el programa paso a paso 
    - Sin generar excepciones
    - Generando la excepción PhantomCollisionException
    - Generando la excepción WallCollisionException

3. Añadir una tercer excepción: ItemColiisionException que sea lanzada al pasar el valor "3" al método move 
    - Manejar desde el método "otro" la excepción PhantomCollisionException y la ItemCollisionException
    - Propagar desde el método "otro" las excepciones WallCollisionException y ItemCollisionException (si, manejarla y - propagarla)
    - Manejar en el método main solo la excepción WallCollisionException 
    - Añadir salidas (System.out.println) a cada método catch de prueba ("A0", "A1", "B1", etc)
    - Entregar como evidencia un pantallazo del código y un pantallazo de la ejecución
