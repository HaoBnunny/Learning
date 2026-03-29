Allocated memory that never got freed
```C
int *p = malloc(sizeof(int));
// you are meant to free this memory after you are done, "free(p);"
```