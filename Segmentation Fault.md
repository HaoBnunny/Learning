Invalid access to memory.
```C
int a[5];
a[6] = 3; // Here, the array only goes uptill index 5 but the programmer accesses the 6th index which doesn't exist in the memory.
```