# Añadir un commit a un repositorio existente

Nota: ejecutar los siguientes des pues de clonar y hace cambios

NOTE: hacer el paso por seguridad
```sh
$ git pull origin master
```
**si sale que hay conflictor hay que hacer las correciones manualmente**

1. verificar si hay cambios en el repo
```sh
cd <project root>
$ git status
```
note: si hay archivos en rojo; significa que existe cambios

2. Añadir archivos para el commit
```sh
# cualquier tipo de archivos
$ git add .
# cuando eliminas archivos
$ git add -A .
```

3. Verificar los archivos que tienes que subir
```sh
$ git status
```
> **note:** los archivos modificados tienen que estar de color verde

4. hacer el commit con un mensage que describa que se realizo durante el commit
```sh
$ git commit -am "<message>"
```

5. subir al repositorio
```sh
$ git push origin master
```
**note:** te pedira las credenciales de github
