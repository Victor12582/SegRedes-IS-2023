## Objetivo
Can you figure out what is in the `eax` register? Put your answer in the picoCTF flag format: `picoCTF{n}` where `n` is the contents of the `eax` register in the decimal number base. If the answer was `0x11` your flag would be `picoCTF{17}`.Download the assembly dump [here](https://artifacts.picoctf.net/c/511/disassembler-dump0_d.txt).
## Solución
```bash
$ cat disassembler-dump0_d.txt 
<+0>:     endbr64 
<+4>:     push   rbp
<+5>:     mov    rbp,rsp
<+8>:     mov    DWORD PTR [rbp-0x14],edi
<+11>:    mov    QWORD PTR [rbp-0x20],rsi
<+15>:    mov    DWORD PTR [rbp-0x4],0x9fe1a
<+22>:    cmp    DWORD PTR [rbp-0x4],0x2710
<+29>:    jle    0x55555555514e <main+37>
<+31>:    sub    DWORD PTR [rbp-0x4],0x65
<+35>:    jmp    0x555555555152 <main+41>
<+37>:    add    DWORD PTR [rbp-0x4],0x65
<+41>:    mov    eax,DWORD PTR [rbp-0x4]
<+44>:    pop    rbp
<+45>:    ret
<+15>:    mov    DWORD PTR [rbp-0x4],0x9fe1a
==
picoCTF{654773}
```
- se compara si 0x9fe1a es menor igual a 0x2710, lo que es falso, por lo que no se cumple la condicion para saltar a <main+37>

```shell
<+37>:    add    DWORD PTR [rbp-0x4],0x65
```

- Le restamos 0x65 a 0x9fe1a, despues se saltara a <main+41>

```shell
<+41>:    mov    eax,DWORD PTR [rbp-0x4]
```

- Le asignaremos el resultado a la variable `eax` que es 0x9fdb5, en decimal seria: `654773`
## Notas
EASYPEASY
