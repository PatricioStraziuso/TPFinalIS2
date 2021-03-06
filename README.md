# TPFinalIS2

Consigna 

Crear los siguientes tests para ambas clases:

    Probar que funcionen según se espera los siguientes métodos:
        getNombreApellido
        getDNI
        getSalario
        setSector y getSector
        __toString()
    Probar que si intento construir un empleado con el nombre vacío, lanza una excepción.
    Probar que si intento construir un empleado con el apellido vacío, lanza una excepción.
    Probar que si intento construir un empleado con el dni vacío, lanza una excepción.
    Probar que si intento construir un empleado con el salario vacío, lanza una excepción.
    Probar que si intento construir un empleado cuyo DNI contenga letras o caracteres no numéricos, lanza una excepción.
    Probar que si, al intentar construir un empleado, no se especifica el sector, el método getSector debe devolver la cadena “No especificado”.

Para la clase EmpleadoEventual, crear los siguientes tests.

    Probar que el método calcularComision() funciona como se espera.
    Probar que el método calcularIngresoTotal() funciona como se espera.
    Probar que si intento construir un empleado proporcionando algún monto de venta negativo o cero, lanza una excepción.

Para la clase EmpleadoPermanente, crear los siguientes tests.

    Probar que el método getFechaIngreso() funciona como se espera. (Leer la documentación para el objeto DateTime de php.net).
    Probar que el método calcularComision() funciona como se espera.
    Probar que el método calcularIngresoTotal() funciona como se espera.
    Probar que el método calcularAntiguedad() funciona como se espera para un empleado con varios años de antigüedad.
    Probar que, si construyo un empleado sin proporcionar la fecha de ingreso, el método getFechaIngreso() retorna la fecha del día, y el método getAntiguedad retorna 0.
    Probar que, si construyo un empleado proporcionando una fecha de ingreso posterior a la de hoy, lanza una excepción.

Implementar integración continua, automatizando la ejecución de los tests unitarios con GitHub Actions.
