The process of 
- Removing Comments
- Expanding Macros & include files
- Conditional statements evaluation
This process outputs an '.i' file
You can run solely the pre-processing stage to generate an '.i' by doing the following command:
```Shell
gcc -E example.c -o example.i
clang -E example.c -o example.i
```

