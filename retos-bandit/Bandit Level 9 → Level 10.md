## Level 9 → Level 10
## Objetivo
The password for the next level is stored in the file **data.txt** in one of the few human-readable strings, preceded by several ‘=’ characters.
## Datos de acceso al nivel
```
bandit 9
EN632PlfYiZbn3PhVK3XOGSlNInNE00t
```
## Solución
```bash
bandit9@bandit:~$ cat data.txt | strings -n 12
4========== the#
========== password
========== is
========== G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
bandit9@bandit:~$ cat data.txt | strings -n 12 | grep "=="
4========== the#
========== password
========== is
========== G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
bandit9@bandit:~$
```

## Notas adicionales
Hice un pish (|) para concatenar lo que mas quiero hacer, despues quiero que solo sean cadenas string y pongo (strings) y -n es para decir el tamaño que necesito de cadena de texto y el grep es para saber con que cosas voy a interponer.
## Referencias
