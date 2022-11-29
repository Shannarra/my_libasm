# my_libasm
A university project consisting of creating some important STDC functions in x86_64 ASM.

## Contents
This repo implements a couple of STDC functions in pure assembly and calls them over in c. The functions implemented are:

  [STDC name] -> project name
- strlen      -> my_strlen
- strchr      -> my_strchr
- memset      -> my_memset
- memcpy      -> my_memcpy
- strcmp      -> my_strcmp
- memmove     -> my_memmove

- strncmp     -> my_strncmp
- strcasecmp  -> my_strcasecmp
- index       -> my_index

- read        -> my_read
- write       -> my_write

## Prerequisites
You will need:
- Netwide Assembler ([nasm](https://www.nasm.us/)) and a 64-bit processor (duuh...)
- [gcc](https://gcc.gnu.org/install), I am using 9.4.0 as of writing this project readme.
- `make`

## Running:
Just run
```
make re && ./my_libasm
```

> Note that "re" is optional and is useful if you want to rebuild every time you run the app. Useful for development.

## Authors and contributing
Petar Angelov ([Shannarra](https://www.github.com/Shannarra)).

If you want to contribute to this project just open a PR with your changes.
