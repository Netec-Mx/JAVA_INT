> Para reforzar la teoría vista hasta el momento haremos unos cambios al proyecto de banca electronica para hacer uso de la API de fechas de Java.

## Objetivos ##

> Reforzar funcionalidad de los métodos de las APIs de fechas que ofrece Java.

### Planteamiento inicial: ###

> Hasta el momento hemos manejado las fechas en un formato de cadenas. Pero ahora cambiaremos todos los atributos que representan una fecha a LocalDate.

Los atributos que cambiaremos son los siguientes:

* fechaNacimiento (Cliente)
* fechaApertura (Cuenta)
* fechaCancelacion (Cuenta)

Realiza los cambios en los atributos y métodos para que el código continue funcionando.

Aparte, agrega una validación para que si un usuario intenta registrarse y es menor de edad (menos de 18 años), le mande una excepción.

Recuerda que en la práctica anterior realizamos una lectura de cuentas desde un archivo. Se debe realizar el cambio para que ahora la cadena del archivo la convierta a un objeto de tipo LocalDate.

Comprobar que todos los métodos sigan funcionando.