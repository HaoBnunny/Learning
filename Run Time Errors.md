Errors that occur during your program's execution.
e.g. dividing something by zero
```C
int x; // the programmer initializes x as an int, which automatically sets it's value to zero.
for(int i=0; i<=10; i++){
	int y = i/x; // here the programmer forgets to give a value to X, giving a division by zero error.
}
```