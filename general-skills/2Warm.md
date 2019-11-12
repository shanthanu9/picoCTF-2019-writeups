# 2Warm

Points: 50

## Question

> Can you convert the number 42 (base 10) to binary (base 2)?

### Hint

> Submit your answer in our competition's flag format. For example, if you answer was '11111', you would submit 'picoCTF{11111}' as the flag.

## Solution

Fastest way to convert base 10 to base 2 is to keep removing largest powers of 2.  
So, 42 - 32 = 10  
    10 - 8 = 2  
    2 - 2 = 0

Hence 42 = 32 + 8 + 2 which is 101010 in binary.
