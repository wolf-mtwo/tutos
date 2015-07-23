# Añadir un commit a un repositorio existente

NOTA: ejecutar los siguientes pasos despues de clonar y hace cambios
NOTA: hacer el paso por seguridad
```sh
# si sale que hay conflictor hay que hacer las correciones manualmente
git pull origin master
```

**verificar si hay cambios en el repo**
```sh
cd <project root>
# si hay archivos en rojo; significa que existe cambios
git status
```

**Añadir archivos para el commit**
```sh
# cualquier tipo de archivos
$ git add .
# cuando eliminas archivos
$ git add -A .
```

**verificar los archivos que tienes que subir**
```sh
# los archivos modificados tienen que estar de color verde
$ git status
```

**hacer el commit con un mensage que describa que se realizo durante el commit**
```sh
$ git commit -am "<message>"
```

**subir al repositorio**
```sh
$ git push origin master
```

**note:** te pedira las credenciales de github
