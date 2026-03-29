Referring to freeing up memory twice.
```C
int *p=malloc(sizeof(int));
free(p);
free(p); // you can't free the same memory space twice
```