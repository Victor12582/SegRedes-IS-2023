## Objetivo
## Solución
```bash
hervi-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/15/level2.py
hervi-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/15/level2.flag.txt.enc
hervi-picoctf@webshell:~$ nano level
level1.flag.txt.enc  level1.py            level2.flag.txt.enc  level2.py
hervi-picoctf@webshell:~$ nano level2.py 
hervi-picoctf@webshell:~$ python level2.py 
Please enter correct password for flag: 39ce
Welcome back... your flag, user:
picoCTF{tr45h_51ng1ng_502ec42e}
hervi-picoctf@webshell:~$ 
```
## Comentarios
Tenía que unirme con el nano para ver como es que debía de ser la contraseña encriptada en ASCII y solamente hubo que convertirla a string y salió 39ce