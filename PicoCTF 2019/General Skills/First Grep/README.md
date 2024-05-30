# Description

## Can you find the flag in file? This would be really tedious to look through manually, something tells me there is a better way.

https://jupiter.challenges.picoctf.org/static/495d43ee4a2b9f345a4307d053b4d88d/file

### Author: Alex Fulton/Danny Tunitis

#### Solution
```bash
x3luminic-picoctf@webshell:~/picoCTF_2019/general_skills$ cat file | grep "picoCTF"
picoCTF{grep_is_good_to_find_things_dba08a45}
```