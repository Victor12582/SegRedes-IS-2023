## Objetivo
Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/515f19f3612bfd97cd3f0c0ba32bd864/file)? This would be really tedious to look through manually, something tells me there is a better way.
## Solución
```bash
hervi-picoctf@webshell:~$ wget https://jupiter.challenges.picoctf.org/static/515f19f3612bfd97cd3f0c0ba32bd864/file
hervi-picoctf@webshell:~$ grep picoCTF file
picoCTF{grep_is_good_to_find_things_5af9d829}
```