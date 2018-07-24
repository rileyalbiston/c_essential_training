# 8. Decisions and Branching

```
cd /cygdrive/d/c_essential_training/8_decisions_and_branching
```

**Using if statements to change program flow**

Basic structure:
```
if(condition)
    doSomething;
```

Comiple and run exercise file:
```
gcc 08_01.c -o 08_01 -std=gnu99 -g -Wall -Werror

./08_01
```

**Using if-else statements to make decisions**

Basic structure:
```
if(condition)
    doSomething;
else
    doSomethingElse;
```

Comiple and run exercise file:
```
gcc 08_02.c -o 08_02 -std=gnu99 -g -Wall -Werror

./08_02
```

**Building alternative decision blocks with if-else-if statements**

Basic structure:
```
if(currentSpeed < maxSpeed)
    printf("You are driving at legal speed \n");
else
    if(currentSpeed == maxSpeed)
        printf("Be careful, slow down a bit \n");
    else
        printf("Slow down now! \n");
```

Comiple and run exercise file:
```
gcc 08_03.c -o 08_03 -std=gnu99 -g -Wall -Werror

./08_03
```

**Building complex decision statements with switch statements**

Basic structure:
```
switch(trafficLightColor)
	case 'r':
		stopDriving();
		break;
	case 'y':
		getReadyToMove();
		break;
	case 'g':
		youCanDriveNow();
		break;
	default:
		trafficLightMalfunction();
```

Comiple and run exercise file:
```
gcc 08_04.c -o 08_04 -std=gnu99 -g -Wall -Werror

./08_04
```

**Challenge: Build a decision-making program**

* Use decision handling in C
* Use *if-else* and *switch* statements
* Build a stock purchase decsion advisor:
> * Ask for the current value of the stock
> * Check the decision parameters
> * Advise to either purchase, sell, or hold
> * Write a function that will check the user input, against preset values using nested *if-else* statements
> * Call another function that will implement a switch construct to handle the purchase, selling or hold decisions
> * Print out the message to the user that informs about the decision

**Solution: Build a decision-making program**

Comiple and run exercise file:
```
gcc 08_06.c -o 08_06 -std=gnu99 -g -Wall -Werror

./08_06
```