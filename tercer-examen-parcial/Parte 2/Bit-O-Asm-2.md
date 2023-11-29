## Objetivo
Can you figure out what is in the `eax` register? Put your answer in the picoCTF flag format: `picoCTF{n}` where `n` is the contents of the `eax` register in the decimal number base. If the answer was `0x11` your flag would be `picoCTF{17}`.Download the assembly dump [here](https://artifacts.picoctf.net/c/510/disassembler-dump0_b.txt).
## Solución
```bash
$ cat disassembler-dump0_b.txt 
<+0>:     endbr64 
<+4>:     push   rbp
<+5>:     mov    rbp,rsp
<+8>:     mov    DWORD PTR [rbp-0x14],edi
<+11>:    mov    QWORD PTR [rbp-0x20],rsi
<+15>:    mov    DWORD PTR [rbp-0x4],0x9fe1a
<+22>:    mov    eax,DWORD PTR [rbp-0x4]
<+25>:    pop    rbp
<+26>:    ret
picoCTF{654874}
```
## Notas
<+22>: mov eax,DWORD PTR [rbp-0x4] Esta instrucción mueve el valor almacenado en la ubicación de memoria apuntada por rbp-0x4 al registro eax.
<+26>: ret Esta instrucción indica el final de la función y devuelve el control al llamador. 
Como podemos ver, se nos dice que se mueve a la variable `eax` el valor de laubicación de memoria apuntada por rbp-0x4. el cual seria `0x9fe1a`, que en deciamal es: 654874