# 📚 Libft – The Standard C Library Reinvented

Libft is a custom implementation of standard C library functions. This project is designed to help understand how fundamental functions like `strlen`, `strcpy`, `malloc`, and more work behind the scenes.

## 🚀 Features
- Reimplementation of essential `string.h`, `stdlib.h`, and `ctype.h` functions.
- Additional utility functions to simplify C development.
- Hands-on experience with memory management.

## 🛠 Installation & Compilation
```sh
make
```
This will generate libft.a, a static library that can be used in your C projects.

To compile a C file using libft.a, use:
```sh
gcc {your_file.c} -L. -lft -o {your_program}
```
Or, if you need to explicitly link the header:
```sh
gcc {your_file.c} libft.a -I./ -o {your_program}
```

## 📜 Usage example
```c
#include "libft.h"

char *str = ft_strdup("Hello, world!");
printf("%s\n", str);
free(str);

```
