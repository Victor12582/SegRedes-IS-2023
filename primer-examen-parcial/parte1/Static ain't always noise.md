## Objetivo
Can you look at the data in this binary: [static](https://mercury.picoctf.net/static/e9dd71b5d11023873b8abe99cdb45551/static)? This [BASH script](https://mercury.picoctf.net/static/e9dd71b5d11023873b8abe99cdb45551/ltdis.sh) might help!
## Solucion
```bash
wget https://mercury.picoctf.net/static/e9dd71b5d11023873b8abe99cdb45551/static
hervi-picoctf@webshell:~$ ls
README.txt  flag  static  static.1  warm
hervi-picoctf@webshell:~$ chmod +x static
hervi-picoctf@webshell:~$ chmod +x static
hervi-picoctf@webshell:~$ strings static | grep pico
picoCTF{d15a5m_t34s3r_ae0b3ef2}
```

