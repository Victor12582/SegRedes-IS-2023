## Objetivo
Attackers have hidden information in a very large mass of data in the past, maybe they are still doing it.Download the data [here](https://artifacts.picoctf.net/c/125/anthem.flag.txt).
## Solución
```bash
hervi-picoctf@webshell:~$ strings anthem.flag.txt | grep pico
      we think that the men of picoCTF{gr3p_15_@w3s0m3_58f5c024}
```
## Notas
Después de descargarlo solo buscamos un pico con el grip en el strings del archivo txt.