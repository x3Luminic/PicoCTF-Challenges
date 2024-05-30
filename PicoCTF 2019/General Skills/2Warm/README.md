# Description

## Can you convert the number 42 (base 10) to binary (base 2)?

### Author: Sanjay C/Danny Tunitis

#### Solution

In binary, values are read as 1s and 0s. Each bit represents 2^(n) where the most right is 2^(0) and the most left is 2^(n). With this information, how can we match 42?

```
Calculation = 2^(6) + 2^(4) + 2^(1)
            = 32 + 8 + 2
            = 42
```

Thus our answer should look like this: 0010 1010

Answer: 0010 1010

We have to remove leading zeros to match the flag requirement

picoCTF{101010}