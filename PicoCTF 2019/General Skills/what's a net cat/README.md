# Description

## Using netcat (nc) is going to be pretty important. Can you connect to jupiter.challenges.picoctf.org at port 64287 to get the flag?

### Author: Sanjay C/Danny Tunitis

#### Solution

Netcat: A networking tool that makes UDP and/or TCP connections. Usage:

`nc <ip-address> <port> `

```bash
x3luminic-picoctf@webshell:~$ nc jupiter.challenges.picoctf.org 64287
You're on your way to becoming the net cat master

picoCTF{nEtCat_Mast3ry_284be8f7}
```