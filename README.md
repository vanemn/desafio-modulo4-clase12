# Proyecto: Instancias de Usuario

## Descripción
Este proyecto consiste en un script de Python que permite crear instancias de usuario a partir de los datos proporcionados en un archivo usuarios.txt. Cada línea del archivo contiene datos en formato JSON que corresponden a los atributos de la clase Usuario. El script lee cada línea, crea una instancia de Usuario y maneja posibles excepciones, registrando cualquier error en un archivo error.log.
Archivos Proporcionados:

### usuario.py:
Contiene la definición de la clase Usuario.

### usuarios.txt:
Contiene los datos de los usuarios en formato JSON, uno por línea.

Se generan los siguientes archivos para su funcionamiento:

### script.py:
Script principal que lee los datos, crea las instancias de Usuario y maneja las excepciones.

### error.log:
Almacena los errores  registrados


## Ejecución del Script

Para ejecutar el script, asegúrate de que todos los archivos (usuario.py, usuarios.txt, script.py, error.log) estén en el mismo directorio. 
Luego, ejecuta el siguiente comando en la terminal:

python script.py
