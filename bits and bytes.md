Computers use bits to store data. A bit can have 2 states: 1 and 0. A single bit can't really hold that much data as you can tell, but when you use 8 of them you can store... a single character (or a number as high as 255)! By the way 8 bits = 1 byte.
Say you typed the character "a" (notice how it's lowercase). The computer would see this character as "0110 0001".
But a byte is still so small, so how can we store a lot of data? Well the binary system doesn't work like the decimal one (the one we use: 0-10). As an example 0000 1010 in binary equals 10 in the decimal system. That's because we take the two bits (and their respective positions) and do the following:
we take the bit's position (n) and use it as follows: 2^n-1.

1010

2^3 + 0 + 2^1 + 0 = 8 + 2 = 10
