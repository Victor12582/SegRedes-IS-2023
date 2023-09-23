## Level 3 → Level 4
## Objetivo
The password for the next level is stored in a hidden file in the **inhere** directory.
## Datos de acceso al nivel
```
bandit3
aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG
```
## Solución
```bash
bandit3@bandit:~$ pwd
/home/bandit3
bandit3@bandit:~$ ls
inhere
bandit3@bandit:~$ cd inhere/
bandit3@bandit:~/inhere$ pwd
/home/bandit3/inhere
bandit3@bandit:~/inhere$ ls
bandit3@bandit:~/inhere$ ls -a
.  ..  .hidden
bandit3@bandit:~/inhere$ cat .hidden
2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe
bandit3@bandit:~/inhere$
```
## Notas adicionales
(ls -a) Significa que me va a mostrar los archivos que están ocultos ya que tienen un punto antes de su nombre.
## Referencias