a)

El Shell es un intérprete de comandos que actúa como interfaz entre el usuario y el sistema operativo. Su función es recibir e interpretar las órdenes ingresadas por el usuario y gestionar su ejecución. Además, permite ejecutar programas y scripts, manejar variables de entorno, realizar redirecciones de entrada y salida y conectar comandos mediante pipes.

b)

Algunos intérpretes de comandos disponibles para GNU/Linux son Bash, C Shell y Korn Shell.

Bash (Bourne Again Shell) pertenece a la familia de Bourne Shell y es ampliamente utilizado en GNU/Linux, incorporando características como historial, autocompletado, redirecciones y scripting.

C Shell (csh) utiliza una sintaxis influenciada por el lenguaje C y posee características orientadas al uso interactivo.

Korn Shell (ksh) mantiene compatibilidad con la familia Bourne e incorpora funciones adicionales, combinando características de Bourne Shell y C Shell.

c)

Los comandos propios o internos del Shell están implementados dentro del mismo intérprete, por lo que no poseen necesariamente un archivo ejecutable con un path en el filesystem.

En cambio, los comandos externos son programas almacenados en directorios como /bin, /usr/bin o /usr/local/bin. El Shell utiliza la variable de entorno PATH para determinar en qué directorios debe buscar estos comandos externos.
