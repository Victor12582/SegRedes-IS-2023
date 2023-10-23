## Objetivo
https://jupiter.challenges.picoctf.org/static/52084b5ad360b25f9af83933114324e0/1000.tar
Desempaquetar 1000 veces de una forma rapida este archivo comprimido
## Solución
```bash
hervi-picoctf@webshell:~$ wget http:..........
hervi-picoctf@webshell:~$ for i in {1000..1}; do tar -xvf $i.tar;rm $i.tar; done
picoCTF{l0t5_0f_TAR5}
```
## Notas