## Level 1 → Level 2
## Objetivo
The password for the next level is stored in a file called **-** located in the home directory.
## Datos de acceso al nivel
```
bandit1
NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL
```
## Solución
```bash
bandit1@bandit:~$ whoami
bandit1
bandit1@bandit:~$ ls
-
bandit1@bandit:~$ cat ./-
rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
bandit1@bandit:~$ pwd
/home/bandit1
bandit1@bandit:~$ cat /home/bandit1/-
rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
bandit1@bandit:~$
```
## Notas adicionales
puedo anteponer un (./) antes de la ruta del archivo para poder verlo, ya que el menos se expresa como una forma de agregar parámetros a un archivo, entonces para ahora si leerlo debemos de poner ./ para poder acceder, antes del nombre. O bien especificar la ruta completa del archivo.
## Referencias
[Google Search for “dashed filename”](https://www.google.com/search?q=dashed+filename)