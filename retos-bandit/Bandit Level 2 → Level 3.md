## Level 2 → Level 3 
## Objetivo
The password for the next level is stored in a file called **spaces in this filename** located in the home directory.
## Datos de acceso al nivel
```
bandit2
rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
```
## Solución
```bash
bandit2@bandit:~$ pwd
/home/bandit2
bandit2@bandit:~$ ls
spaces in this filename
bandit2@bandit:~$ cat "spaces in this filename"
aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG
bandit2@bandit:~$
```
## Notas adicionales
Para ver un archivo que tiene muchos espacios en el nombre debes de escribirlo entre comillas.
## Referencias
[htu-oqct-fyy (2023-08-30 10:06 GMT-6) - Google Drive](https://drive.google.com/file/d/1TIeDsWkaWyH1ME4Z9nxq796EOOpJCp3N/view?pli=1)
