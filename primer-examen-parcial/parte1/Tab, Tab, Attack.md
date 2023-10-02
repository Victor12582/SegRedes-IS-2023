## Objetivo
Using tabcomplete in the Terminal will add years to your life, esp. when dealing with long rambling directory structures and filenames: [Addadshashanammu.zip](https://mercury.picoctf.net/static/a350754a299cb58988d6d47aed5be3ba/Addadshashanammu.zip)
## Solución
```bash
hervi-picoctf@webshell:~$ wget URL
hervi-picoctf@webshell:~$ unzip Addadshashanammu.zip                        
hervi-picoctf@webshell:~$ cd Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku/
hervi-picoctf@webshell:~/Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurna
bitashpi/Maelkashishi/Onnissiralis/Ularradallaku$ ls .la
ls: cannot access '.la': No such file or directory
hervi-picoctf@webshell:~/Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurna
bitashpi/Maelkashishi/Onnissiralis/Ularradallaku$ ls -la
total 12
drwxr-xr-x 2 hervi-picoctf hervi-picoctf   35 Mar 16  2021 .
drwxr-xr-x 3 hervi-picoctf hervi-picoctf   27 Mar 16  2021 ..
-rwxr-xr-x 1 hervi-picoctf hervi-picoctf 8320 Mar 16  2021 fang-of-haynekhtnamet
hervi-picoctf@webshell:~/Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurna
bitashpi/Maelkashishi/Onnissiralis/Ularradallaku$ ./fang-of-haynekhtnamet 
*ZAP!* picoCTF{l3v3l_up!_t4k3_4_r35t!_a00cae70}
```
