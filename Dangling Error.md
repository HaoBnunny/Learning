Referring to freed memory
```C
int *p = malloc(sizeof(int));
free(p);
*p=5; // you are accessing memory that you've freed.
```