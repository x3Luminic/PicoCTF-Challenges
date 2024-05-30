# Description

## I wrote you a song. Put it in the picoCTF{} flag format.

### Author: Danny

### Solution:

The file that we retrieved look like this:

```
Pico's a CTFFFFFFF
my mind is waitin
It's waitin

Put my mind of Pico into This
my flag is not found
put This into my flag
put my flag into Pico


shout Pico
shout Pico
shout Pico

My song's something
put Pico into This

Knock This down, down, down
put This into CTF

shout CTF
my lyric is nothing
Put This without my song into my lyric
Knock my lyric down, down, down

shout my lyric

Put my lyric into This
Put my song with This into my lyric
Knock my lyric down

shout my lyric

Build my lyric up, up ,up

shout my lyric
shout Pico
shout It

Pico CTF is fun
security is important
Fun is fun
Put security with fun into Pico CTF
Build Fun up
shout fun times Pico CTF
put fun times Pico CTF into my song

build it up

shout it
shout it

build it up, up
shout it
```

I had no idea what it was, so I used the hint and it's something to do with Rockstar. After google and doing some research, I found out that it's a programming language. After running the online interpreter, we get this:

```
114
114
114
111
99
107
110
114
110
48
49
49
51
114
```

Which CyberChef helped us decode it from Decimal. 

`rrrocknrn0113r`

Thus the flag is: `picoCTF{rrrocknrn0113r}`