Logic gates are very useful. They're used commonly in circuits and software alike. They're sort of like simpler if statements, since they work with values ranging from 0 to 1.

But what are logic gates? Well, they basically define the relationship between two things, and if that relationship is true they return 1, otherwise 0 (false). As an example 1 == 1 returns true since the statement is correct.

About true and false... these values work the same like 1 and 0 (but fancier) and are called "booleans" or "bools" for short. This is what is mainly used when working with logic gates. The logic gates (finally) come in when you want to check something such as: 1 + 1 == 2 AND 2 + 2 == 4. This is the "AND" logic gate. It returns true if both inputs are the same type. And so this returns true since the first operation returned true and the second too.

Other uses include throwing errors by using the OR logic gate:

```
x=2+1 --x of course equals 3

x==3 OR print("Huh?") --if for some reason x is not 3 print to the console "Huh?"
```

For reference, here's the logic gate's outputs:

|Input|Output|
|:-:|:-:|
|0 OR 0|0|
|0 OR 1|1|
|1 OR 0|1|
|1 OR 1|1|
|0 AND 0|1|
|0 AND 1|0|
|1 AND 0|0|
|1 AND 1|1|
|NOT 0|1|
|NOT 1|0|

You can also combine them! As an example if you use NOT AND you get NAND which has the same output as AND but inverted.
