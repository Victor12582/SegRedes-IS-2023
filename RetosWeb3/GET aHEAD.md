## Objetivo
Find the flag being held on this server to get ahead of the competition [http://mercury.picoctf.net:28916/](http://mercury.picoctf.net:28916/)
## Solución
```bash
hervi-picoctf@webshell:~$ curl -I http://mercury.picoctf.net:28916/
HTTP/1.1 200 OK
flag: picoCTF{r3j3ct_th3_du4l1ty_70bc61c4}
Content-type: text/html; charset=UTF-8
```
## Comentarios
Tenemos que aplicar una atracción de la pagina para conocer las caracteristicas de la misma.

