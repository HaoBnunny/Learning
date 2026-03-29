In C, & many others, datatypes such as integers have a max size limit.
If you go over this max size limit, you "overflow" & the datatype is rolled back to the 1st value it can be, i.e. zero.
```C
int x = 2147483647; // This is the maximum size for a signed integer in C
int y = x + 1; // Here, y will be zero instead of 2147483648
```