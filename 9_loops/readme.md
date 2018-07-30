# 9. Loops

```
cd /cygdrive/d/c_essential_training/9_loops
```

**Executing statements repeatedly with loops**

Basic structure:
```
for(k = START_VALUE; k < MAX_VALUE; k += INCREMENT){
	doSomething;
	doAnotherThing
}
```

Comiple and run exercise file:
```
gcc 09_01.c -o 09_01 -std=gnu99 -g -Wall -Werror

./09_01
```

**Using for loops**

The *for* loop is most approriate when:

* You know the exact number of repetitions needed
* There are no other conditions

The *for* loop is not the best choice when:

* The halting conditions are dynamic
* Waiting for and event to occour

Basic structure:
```
for(k = START_VALUE; k < MAX_VALUE; k += INCREMENT){
	doSomething;
	doAnotherThing
}
```

Comiple and run exercise file:
```
gcc 09_02.c -o 09_02 -std=gnu99 -g -Wall -Werror

./09_02
```

**Using while loops**

Used to repeat code as long as a condition is true. Be sure to always have an end condition for a *while* loop to avoid infinite loops.

Basic structure:
```
while(condition){
	doSomething;
}
```

```
falg = false;

while(!flag){
	readTheNextPage();

	if(charactersToRead == 0){
		printf("You finished the book! \n");
		flag = TRUE;
	}
}
```

Comiple and run exercise file:
```
gcc 09_03.c -o 09_03 -std=gnu99 -g -Wall -Werror

./09_03
```

**Understanding the do-while loop**

Used to repeat code until a condition is false. 

Executes at least once.

Basic Structure:
```
do {
	doSomething;
} while (condition)
```

```
flag = FLASE;

do {
	readTheNextPage();

	if (charactersToRead == 0) {
		printf("You finished the book! \n");
		flag = TRUE;
	}
} while (!flag)
```

Comiple and run exercise file:
```
gcc 09_04.c -o 09_04 -std=gnu99 -g -Wall -Werror

./09_04
```

**Breaking out of loops**

Used to break the loop cycle

Read until end of line unless you read 'x'

Basic Structure:
```
while ((c = get_char()) != '\n') {
	if (c == 'x') {
		break; //stop if you read x
	}
}
```

Comiple and run exercise file:
```
gcc 09_05.c -o 09_05 -std=gnu99 -g -Wall -Werror

./09_05
```

**Challenge: Make a bar chart**

- In this challenge, you will show that you understood how to use loops, which type of loops are most appropriate and solve a little problem that would require you to use loops. The challenge is pretty simple. You are required to display a bar chart. What is a bar chart? It's a set of dots printed horizontally that represent one bar. If you print several of them, one below the other, eventually they will form a bar chart.

You will create one function whose role is to print a single bar. You have to figure out how to do that. Then you'll create another function that calls the first function multiple times each time sending it a different parameter that represents the length of the bar. It is up to you how many bars you want to print, five, ten, or anywhere in between would be a good number but that's totally up to you. Good luck, and by the way, we think this should take you maybe about 20 minutes to figure this out.

**Solution: Make a bar chart**

Comiple and run exercise file:
```
gcc 09_07.c -o 09_07 -std=gnu99 -g -Wall -Werror

./09_07
```
