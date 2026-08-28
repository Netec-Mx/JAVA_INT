# Practica 5: Banca electrónica concurrente. # 
> Para reforzar la teoría vista hasta el momento haremos unos cambios al proyecto de banca electronica para hacer uso de la de Concurrencia de Java.

## Objetivos ##

> Reforzar funcionalidad de los métodos de la API de concurrencia que ofrece Java.

### Planteamiento inicial: ###

> Una de las tareas más pesadas que hace nuestro proyecto hasta el momento es la lectura del archivo de cuentas. Para esta práctica el reto es ejecutar la lectura del archivo en un hilo secundario usando ExecutorService y newSingleThreadExecutor().

El programa se espera que funcione de la siguiente manera:

![Funcionamiento interno](/Imagenes/Capitulo-08-01.png)

Crear un hilo usando ExecutorService para la lectura del archivo de cuentas.txt.

Obtener las cuentas creadas a partir del archivo usando Future y Callable.

Imprimir las cuentas obtenidas por el hilo en el hilo main.

Validar que la aplicación continúe funcionando correctamente.