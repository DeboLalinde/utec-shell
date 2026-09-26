# Shell, archivos de inicialización, variables y expansiones

Scripts de Bash para practicar alias, variables, expansiones y aritmética de shell.

## Scripts

- `0-alias`: crea un alias llamado `ls` con el valor `rm -f *`, que borra todos los archivos del directorio actual. Se carga con `source ./0-alias`.
- `1-hello_you`: imprime "hello" seguido del nombre del usuario actual, usando la variable `USER`.
- `2-path`: agrega `/action` al final de la variable `PATH`, para que sea el último directorio donde se buscan programas. Se carga con `source ./2-path`.
- `3-paths`: cuenta la cantidad de directorios en `PATH`, ignorando las entradas vacías
- `4-global_variables`: lista las variables de entorno (globales) usando `printenv`.
- `5-local_variables`: lista todas las variables locales, las variables de entorno y las funciones usando `set`.
- `6-create_local_variable`: crea una variable local llamada `BEST` con el valor `School`, usando la forma `NOMBRE=valor` (sin `export`).
- `7-create_global_variable`: crea una variable global llamada `BEST` con el valor `School`, usando `export BEST=School`.
- `8-true_knowledge`: imprime el resultado de sumar 128 al valor de la variable `TRUEKNOWLEDGE`.
