# CLI (Commands Line Interface)

## Comandos basicos

Visualizar la ruta del directorio de trabajo actual

    $ pwd

Listar el nombre de los recursos del directorio de trabajo actual

    $ ls

Listar el nombre de los recursos del directorio de trabajo actual, incluyendo recursos ocultos

    $ ls -a

Listar los recursos del directorio actual, incluyendo detalles adicionales como la fecha de ultima modificacion

    $ ls -l

Cambiar de directorio

    $ cd <dir_name>

Regresar a un directorio anterior en la ruta de trabajo actual

    $ cd ..

Regresar 2 directorios en la ruta actual

    $ cd ../..

Visualizar el contenido de un archivo

    $ more <file_name>

Crear un nuevo directorio

    $ mkdir <dir_name>

Crear un nuevo directorio en una ruta diferente a la actual

    $ mdkir <./dir_name/dir_name/new_dir>

Imprimir contenido en la consola

    $ echo <content>

Crear un archivo

    $ touch <file_name>

Copiar recursos y pegarlos en un nuevo directorio

    $ cp <resource_name> <new_dir>

Copiar todos los recursos de un directorio y pegarlos dentro de un nuevo directorio

    $ cp -r <dir_name> <new_dir>

Eliminar un archivo

    $ rm <file_name>

Eliminar un directorio y a los recursos que este contenga

    $ rm -r <dir_name>

Eliminar un directorio vacio

    $ rmdir <dir_name>

Renombrar un recurso del directorio actual
    
    $ mv <current_name> <new_name>

Mover un recurso a un nuevo directorio

    $ mv <resource_name> <new_dir>

Listar a traves de una vista jerarquica (./dir/file~dir) los recursos del directorio de trabajo

    $ find

Listar la ruta de un recurso especifico en la ruta de trabajo actual

    $ find -name <resource_name>

Agregar texto a un archivo

    $ echo <text> >> <file_name>

Leer el contenido de un archivo

    $ cat <file_name>

Cerrar la instancia actual de la linea de Comandos

    $ exit