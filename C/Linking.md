The Final step in building an application is linking.
This is the step that outputs your executable that you can then distribute however you want.
This is where the linker links the definition of functions to the function calls.
It also declares the start & end of your program.
Linking occurs in 2 stages:
- Compile Time
- Load Time
I believe the names are self-explanatory.

For windows:
A linker needs to output an '.exe' file.
```Shell
gcc example.c -o example.exe
clang example.c -o example.exe
```
For Linux/Unix:
A linker needs to output an '.out' file.
```Shell
gcc example.c -o example.out
clang example.c -o example.out
```
[Output File extension may vary across distro's!]
