# Description

## Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to jupiter.challenges.picoctf.org 7480.

### Author: Alex Fulton/Danny Tunitis

#### Solution

When you access it the first time, you'll notice that it is printing alot of lines causing it difficult to search for the flag. To save the output of the nc, you can use ">" to tell the shell that you want to store the output into a file.

```bash
x3luminic-picoctf@webshell:~/picoCTF_2019/general_skills$ nc jupiter.challenges.picoctf.org 7480 > output.txt
x3luminic-picoctf@webshell:~/picoCTF_2019/general_skills$ ls
output.txt
x3luminic-picoctf@webshell:~/picoCTF_2019/general_skills$ cat output.txt | grep picoCTF 
picoCTF{digital_plumb3r_06e9d954}
```