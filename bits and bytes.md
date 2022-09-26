Computers use bits to store data. A bit has 2 states: 1 and 0.

A single bit can't really hold that much data as you can tell, but when you use 8 of them you can store... a single character (or a number as high as 255)! By the way 8 bits = 1 byte.
Say you typed the character "a" (notice how it's lowercase, since it's uppercase variant has a different code). The computer would see this character as "0110 0001".

---

But a byte is still so small and there's only so many combinations, so how can we store really high numbers? Well the binary system doesn't work like the decimal one (the one we use: 0-10). As an example 1010 in binary equals 10 in the decimal system. That's because we take the four bits (and their respective positions) and do the following:
we take the bit's position (n) and use this formula: 2^n-1.

1010 --binary

4321 --bit positions

2^3 + 0 + 2^1 + 0 = 8 + 2 = 10

The first bit (from left to right) is 1 and it's position is 4, so by using 2^n-1 we get 2^3 which is 8. The second is 0 so we simply use 0 and continue until the last bit while adding them together.
