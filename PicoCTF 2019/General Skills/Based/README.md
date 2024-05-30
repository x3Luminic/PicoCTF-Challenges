# Description

## To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337? Connect with nc jupiter.challenges.picoctf.org 29221.

### Author: Alex Fulton/Danny Tunitis

#### Solution

Using CyberChef, there is one operation that makes life much simpler. That is Magic operation. It automatically detects which format is used and give you a possible output result.

```bash
x3luminic-picoctf@webshell:~/picoCTF_2019/general_skills$ nc jupiter.challenges.picoctf.org 29221
Let us see how data is stored
computer
Please give the 01100011 01101111 01101101 01110000 01110101 01110100 01100101 01110010 as a word.
...
you have 45 seconds.....

Input:
computer
Please give me the  164 145 163 164 as a word.
Input:
test
Please give me the 7375626d6172696e65 as a word.
Input:
submarine
You've beaten the challenge
Flag: picoCTF{learning_about_converting_values_00a975ff}
```