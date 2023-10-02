## Objetivo
Run the Python script `code.py` in the same directory as `codebook.txt`.

- [Download code.py](https://artifacts.picoctf.net/c/3/code.py)
- [Download codebook.txt](https://artifacts.picoctf.net/c/3/codebook.txt)
- On the webshell, use `ls` to see if both files are in the directory you are in
- The `str_xor` function does not need to be reverse engineered for this challenge.
## Solución
```bash
C:\Users\manel>cd OneDrive
C:\Users\manel\OneDrive>cd Documentos
C:\Users\manel\OneDrive\Documentos>cd "6to Semestre"
C:\Users\manel\OneDrive\Documentos\6to Semestre>dir
 El volumen de la unidad C es Windows
 El número de serie del volumen es: 30F0-38D8

 Directorio de C:\Users\manel\OneDrive\Documentos\6to Semestre

28/08/2023  10:49 a. m.    <DIR>          .
01/10/2023  05:09 p. m.    <DIR>          ..
01/10/2023  07:12 p. m.    <DIR>          CiberSeguridad
01/10/2023  05:05 p. m.    <DIR>          Lab_Estructura_Datos
               0 archivos              0 bytes
               4 dirs  347,677,253,632 bytes libres
C:\Users\manel\OneDrive\Documentos\6to Semestre>cd CiberSeguridad
C:\Users\manel\OneDrive\Documentos\6to Semestre\CiberSeguridad>dir
 El volumen de la unidad C es Windows
 El número de serie del volumen es: 30F0-38D8

 Directorio de C:\Users\manel\OneDrive\Documentos\6to Semestre\CiberSeguridad

01/10/2023  07:12 p. m.    <DIR>          .
28/08/2023  10:49 a. m.    <DIR>          ..
01/10/2023  07:09 p. m.             1,278 code.py
01/10/2023  07:09 p. m.                27 codebook.txt
01/10/2023  06:29 p. m.    <DIR>          hacknotes
               2 archivos          1,305 bytes
               3 dirs  347,677,253,632 bytes libres
C:\Users\manel\OneDrive\Documentos\6to Semestre\CiberSeguridad>python code.py
picoCTF{c0d3b00k_455157_197a982c}
```
