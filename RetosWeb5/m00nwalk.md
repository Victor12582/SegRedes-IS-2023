## Objetivo
Decode this [message](https://jupiter.challenges.picoctf.org/static/fc1edf07742e98a480c6aff7d2546107/message.wav) from the moon.
## Solución
```bash
sstv -d message.wav -o img.jpg
ls
img.jpg message.wav
open img.jpg
pyhton -c
```
## Notas
Lo que hicimos fue decodificar los beats del audio para ver las imágenes que pueden estar ocultas dentro de un audio.