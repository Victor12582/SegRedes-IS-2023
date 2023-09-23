## Level 4 → Level 5
## Objetivo
The password for the next level is stored in the only human-readable file in the **inhere** directory. Tip: if your terminal is messed up, try the “reset” command.
## Datos de acceso al nivel
```
bandit 4
2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe
```
## Solución
```bash
bandit4@bandit:~/inhere$ file ./-file0*
./-file00: data
./-file01: data
./-file02: data
./-file03: data
./-file04: data
./-file05: data
./-file06: data
./-file07: ASCII text
./-file08: data
./-file09: Non-ISO extended-ASCII text, with no line terminators
bandit4@bandit:~/inhere$ cat ./-file07
lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
bandit4@bandit:~/inhere$
```
## Notas adicionales
(file ./-file0*) Este comando me dice de que tipo de archivo es por el cual yo ando buscando, so como yo estoy buscando un código ASCII rápido me fijo en cual está y entro para ver la contraseña mas fácilmente.
## Referencias