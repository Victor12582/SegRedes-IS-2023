## Objetivo
We found this [packet capture](https://jupiter.challenges.picoctf.org/static/0c84d3636dd088d9fe4efd5d0d869a06/capture.pcap) and [key](https://jupiter.challenges.picoctf.org/static/0c84d3636dd088d9fe4efd5d0d869a06/picopico.key). Recover the flag.
## Solución
```bash
hervi$: ssldump -r capture.pcap -k picopico.key -d | grep pico
o
picoCTF{nongshim.shrimp.crackers}
```
## Notas
Cambiar variable TLS para encriptar la llave que nos da en el enlace y buscar en terminos de paquetes la contraseña.
