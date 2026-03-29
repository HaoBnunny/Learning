These are modifiers that can you use in your commands to change their outputs & have more control over what they do in general.
For example:
```Shell
clang -c test.c // here -c is a short-hand flag
clang --hip-link test.c // here --hip-link is a long-hand flag
clang test.c -o test.o // here -o is a positional flag i.e. specifies where the output goes
```
these 3 types of flags are the extend of knowledge that you will tackle during C development.

> [!NOTE] More flags
```Shell
ls -la // here -la is referred to as a combination flag
rm --no-perseve-root * // here "--no" is a prefix for something known as a negation flag

``` 

