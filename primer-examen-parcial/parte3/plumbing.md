## Objetivo
Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to `jupiter.challenges.picoctf.org 4427`.
## Solución
```bash
hervi-picoctf@webshell:~$ nc jupiter.challenges.picoctf.org 4427
...
...
...
hervi-picoctf@webshell:~$ ls
runme.py
hervi-picoctf@webshell:~$ nc jupiter.challenges.picoctf.org 4427 >> flagout.txt
ls
hervi-picoctf@webshell:~$ ls
flagout.txt  runme.py
hervi-picoctf@webshell:~$ cat flagout.txt | grep pico
picoCTF{digital_plumb3r_5ea1fbd7}
```