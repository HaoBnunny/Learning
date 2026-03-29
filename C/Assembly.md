The process of converting the '.s' file into an object ('.o') file that contains machine-level translations of your code.
This is a binary file, i.e. it contains 1/0's as instructions & unreadable by humans.
However if you look at in your text editor, you may not see the 1/0's but a bunch of random symbols. Just ignore trying to read them, you can't.

You can generate a '.o' by running 
```Shell
gcc -c example.c -o example.o
clang -c example.c -o example.o
```

This file is also the one you will generally run in your terminal to test stuff out instead of something like an '.exe' file.