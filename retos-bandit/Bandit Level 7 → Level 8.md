## Level 7 → Level 8
## Objetivo
The password for the next level is stored in the file **data.txt** next to the word **millionth**
## Datos de acceso al nivel
```
bandit7
z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
```
## Solución
```bash
bandit7@bandit:~$ grep millionth data.txt
millionth       TESKZC0XvTetK0S9xNwm25STk5iWrBvP
bandit7@bandit:~$
```
## Notas adicionales
Grep se utiliza para buscar patrones o palabras especificas y se tiene que decir en donde.
```bash
cat data.txt | |grep millionth
o
grep millionth data.txt
```
## Referencias