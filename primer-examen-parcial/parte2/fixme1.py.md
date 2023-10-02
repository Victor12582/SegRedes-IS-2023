## Objetivo
Fix the syntax error in this Python script to print the flag.[Download Python script](https://artifacts.picoctf.net/c/27/fixme1.py)
## Solución
```bash
hervi-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/27/fixme1.py
hervi-picoctf@webshell:~$ ls
README.txt  convertme.py  file  fixme1.py
hervi-picoctf@webshell:~$ python fixme1.py 
  File "/home/hervi-picoctf/fixme1.py", line 20
    print('That is correct! Here\'s your flag: ' + flag)
IndentationError: unexpected indent
hervi-picoctf@webshell:~$ nano fixme1.py
hervi-picoctf@webshell:~$ nano fixme1.py
hervi-picoctf@webshell:~$ python fixme1.py 
That is correct! Here's your flag: picoCTF{1nd3nt1ty_cr1515_182342f7}
```