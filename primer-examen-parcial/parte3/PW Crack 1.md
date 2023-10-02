## Objetivo
Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/10/level1.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/10/level1.flag.txt.enc) in the same directory too.
## Solución
```bash
hervi-picoctf@webshell:~$ cat level1.   
cat: level1.: No such file or directory
hervi-picoctf@webshell:~$ cat 
.bash_history        .local/              .wget-hsts           level1.flag.txt.enc
.bash_logout         .profile             README.txt           level1.py
.bashrc              .ssh/                fixme2.py            strings
hervi-picoctf@webshell:~$ cat level1.flag.txt.enc 
FPR
   umw
iK
_i
  UDhervi-picoctf@webshell:~$ cat level1.py 
### THIS FUNCTION WILL NOT HELP YOU FIND THE FLAG --LT ########################
def str_xor(secret, key):
    #extend key to secret length
    new_key = key
    i = 0
    while len(new_key) < len(secret):
        new_key = new_key + key[i]
        i = (i + 1) % len(key)        
    return "".join([chr(ord(secret_c) ^ ord(new_key_c)) for (secret_c,new_key_c) in zip(secret,new_key)])
###############################################################################


flag_enc = open('level1.flag.txt.enc', 'rb').read()



def level_1_pw_check():
    user_pw = input("Please enter correct password for flag: ")
    if( user_pw == "691d"):
        print("Welcome back... your flag, user:")
        decryption = str_xor(flag_enc.decode(), user_pw)
        print(decryption)
        return
    print("That password is incorrect")



level_1_pw_check()
hervi-picoctf@webshell:~$ python level1.py 
Please enter correct password for flag: 691d
Welcome back... your flag, user:
picoCTF{545h_r1ng1ng_56891419}
```