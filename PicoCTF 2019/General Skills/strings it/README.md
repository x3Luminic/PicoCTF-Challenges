# Description

## Can you find the flag in file without running it?

### Author: Sanjay C/Danny Tunitis

### Solution:

The file that we will need is here: https://jupiter.challenges.picoctf.org/static/5bd86036f013ac3b9c958499adf3e2e2/strings

The hint is already given which is to strings the file. However when we run the command, there's a lot of rubbish and a way to solve that is to include the pipe with grep. This allows us to match a specific set of characters which we know the flag contains: picoCTF.

So to solve this, we just need to run this command:

strings <file> | grep "picoCTF"
picoCTF{5tRIng5_1T_827aee91}
