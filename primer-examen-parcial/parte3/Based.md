## Objetivo
To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337? Connect with `nc jupiter.challenges.picoctf.org 29956`.
## Solución
```bash
hervi-picoctf@webshell:~$ nc jupiter.challenges.picoctf.org 29956
Let us see how data is stored
pear
Please give the 01110000 01100101 01100001 01110010 as a word.
...
you have 45 seconds.....

Input:
pear
Please give me the  164 145 163 164 as a word.
Input:
test
Please give me the 616e696d6174696f6e as a word.
Input:
animation
You've beaten the challenge
Flag: picoCTF{learning_about_converting_values_b375bb16}
```
## Comentarios
Tenemos que ser rápidos para encontrar la codificación en Binary, Octal y ASCII