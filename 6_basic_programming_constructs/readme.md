# 6. Basic Prgramming COnstructs

```
cd /cygdrive/d/c_essential_training/6_basic_programming_constructs
```

**Understanding the use of arithmetic operators**

| Group 1 			| Group 2 					|
|-------------------|---------------------------|
| + addition		| % modulus					|
| - subtraction 	| ++ increment integer by 1 |
| * multiplication 	| -- decrement integer by 1 |
| / division 		|							|

Comiple and run exercise file:
```
gcc 06_01.c -o 06_01 -std=gnu99 -g -Wall -Werror

./06_01
```

**Understanding the use of relational operators**

| Group 1 			| Group 2 					  | Group 3 	   |
|-------------------|-----------------------------|----------------|
| ! not  			| > greater than			  | && logical and |
| == is equal		| < less than				  | || logical or  |
| != is not equal 	| >= greater than or equal to |				   |
|					| <= less than or equal to    |				   |

Comiple and run exercise file:
```
gcc 06_02.c -o 06_02 -std=gnu99 -g -Wall -Werror

./06_02
```

**Making decisions using logical operators**

Recall the logical operators: \&& = AND, || = OR

Logical operators can be used to make decisions

leverage the fact that 1 = true, 0 = false

Comiple and run exercise file:
```
gcc 06_03.c -o 06_03 -std=gnu99 -g -Wall -Werror

./06_03
```

**Performing bit-level calculations with bitwise operations**

Comiple and run exercise file:
```
gcc 06_04.c -o 06_04 -std=gnu99 -g -Wall -Werror

./06_04
```

**Using assignment operators in complex statements**

Comiple and run exercise file:
```
gcc 06_05.c -o 06_05 -std=gnu99 -g -Wall -Werror

./06_05
```

**Implementing mathematical expressions**

Comiple and run exercise file:
```
gcc 06_06.c -o 06_06 -std=gnu99 -g -Wall -Werror

./06_06

gcc 06_06a.c -o 06_06a -std=gnu99 -g -Wall -Werror

./06_06a
```

**Understanding the relationship between statements and expressions**

Comiple and run exercise file:
```
gcc 06_07.c -o 06_07 -std=gnu99

./06_07
```

**Challenge: Convert centimeters to feet and inches**

Write a program in C that receives as input a height in centimeters. The problem will then calculate and display the following: The height in feet and inches.

All you have to do is figure out what is the conversion between inches, feet, and centimeters. Be a little bit creative with the way you develop the math, and use everything you learned so far about calculations, variables, expressions, math and statements, and write a very short and simple program in C.

**Solution: Convert centimeters to feet and inches**

Comiple and run exercise file:
```
gcc 06_09.c -o 06_09 -std=gnu99

./06_09
```

**Challenge: Convert temperatures**

Convert degrees from Celsius to Fahrenheit and Kelvin. It is known that water freezes at zero degrees Celsius and boils at 100 degrees Celsius.

Right a program in C that will calculate the freezing and boiling temperature of water in Fahrenheit and Kelvin degrees. For this exercise, use the following formulas, degree Fahrenheit equal degree Celsius times nine over five plus 32. And, Kelvin equals degrees in Celsius plus 273.

**Solution: Convert temperatures**

Comiple and run exercise file:
```
gcc 06_11.c -o 06_11 -std=gnu99

./06_11
```
