## Objetivo
 [This program](https://mercury.picoctf.net/static/fc1d77192c544314efece5dd309092e3/warm) has extraordinarily helpful information. 
 This program will only work in the webshell or another Linux computer.
## Solución
```bash
hervi-picoctf@webshell:~$ wget https://mercury.picoctf.net/static/fc1d77192c544314efece5dd309092e3/warm
hervi-picoctf@webshell:~$ ls -la
-bash: ./warm: Permission denied
hervi-picoctf@webshell:~$ chmod +w warm 
hervi-picoctf@webshell:~$ ./warm
-bash: ./warm: Permission denied
hervi-picoctf@webshell:~$ ./warm -h
-bash: ./warm: Permission denied
hervi-picoctf@webshell:~$ ./warm   
-bash: ./warm: Permission denied
hervi-picoctf@webshell:~$ chmod +x warm
hervi-picoctf@webshell:~$ ./warm 
Hello user! Pass me a -h to learn what I can do!
hervi-picoctf@webshell:~$ ./warm -h
Oh, help? I actually don't do much, but I do have this flag here: picoCTF{b1scu1ts_4nd_gr4vy_6635aa47}
```
## Notas adicionales
## Referencias