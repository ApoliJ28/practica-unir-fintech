# Repo para EIEC - DevOps - UNIR

Este repositorio nos servirá para demostrar el uso de Git en la asignatura de EIEC y muchas cosas mas.

---

Los comandos del Makefile funcionarán en Linux y MacOS. En caso de usar Windows, necesitarás adaptarlos o ejecutarlos en una máquina virtual Linux.

## Ejecución

```bash
python3 main.py <filename> <dup>
```

- `filename`: **ruta** al fichero que contiene la lista de palabras, una por línea.
- `dup`: **yes|no**, `yes` para eliminar palabras duplicadas, `no` para mantener la lista.

## Ejecución de prueba

Con un fichero `words.txt` que contiene:

```text
gryffindor
slytherin
hufflepuff
ravenclaw
gryffindor
```

Ejecutamos la aplicación eliminando duplicados:

```bash
$ python3 main.py words.txt yes
The words will be read from the file words.txt
['slytherin', 'ravenclaw', 'hufflepuff', 'gryffindor']
```