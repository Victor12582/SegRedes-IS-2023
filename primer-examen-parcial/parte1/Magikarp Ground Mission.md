## Objetivo
Do you know how to move between directories and read files in the shell? Start the container, `ssh` to it, and then `ls` once connected to begin. Login via `ssh` as `ctf-player` with the password, `6dee9772`
ssh ctf-player@venus.picoctf.net -p 57965
## Solución
```bash
hervi-picoctf@webshell:~$ ssh ctf-player@venus.picoctf.net -p 57965
picoCTF{xxsh_
ctf-player@pico-chall$ cd /
ctf-player@pico-chall$ ls
2of3.flag.txt  dev   instructions-to-3of3.txt  media  proc  sbin  tmp
bin            etc   lib                       mnt    root  srv   usr
boot           home  lib64                     opt    run   sys   var
ctf-player@pico-chall$ cat 2of3.flag.txt 
0ut_0f_\/\/4t3r_
ctf-player@pico-chall$ cd ~
ctf-player@pico-chall$ ls
3of3.flag.txt  drop-in
ctf-player@pico-chall$ cat 3of3.flag.txt 
540e4e79}

picoCTF{xxsh_0ut_0f_\/\/4t3r_540e4e79}

```