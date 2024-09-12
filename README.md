# libft

## Description

`libft` is a custom implementation of a standard C library. It provides a collection of commonly used C functions, including functions for string manipulation, memory management, conversions, and handling linked lists. The library is designed to be modular and reusable, providing a foundation for more advanced C projects.

## Features

- **String manipulation**:
  - Functions like `ft_strlen`, `ft_strlcpy`, `ft_strjoin`, and more, for easy and efficient handling of C strings.
  
- **Memory management**:
  - Functions such as `ft_memset`, `ft_memcpy`, and `ft_calloc` for low-level memory operations.

- **Character checks and conversions**:
  - Functions like `ft_isalpha`, `ft_isdigit`, `ft_tolower`, and `ft_toupper` to validate and convert characters.

- **Linked lists**:
  - A set of functions to create and manipulate linked lists, including `ft_lstnew`, `ft_lstadd_back`, `ft_lstmap`, and others.

- **File and number handling**:
  - Functions like `ft_itoa`, `ft_putchar_fd`, `ft_putstr_fd`, `ft_putnbr_fd` to convert and output data to file descriptors.

## Usage

To use `libft` in your project:

1. Include the library header in your code:
    ```c
    #include "libft.h"
    ```

2. Compile `libft` using the provided Makefile:
    ```bash
    make
    ```

3. Link the resulting `libft.a` archive with your project:
    ```bash
    gcc -o my_program my_program.c -L. -lft
    ```

4. Use the functions as needed in your project:
    ```c
    char *str = ft_strdup("Hello, World!");
    printf("%s\n", str);
    free(str);
    ```

## Installation

Clone this repository and build the library:

```bash
git clone https://github.com/girts521/libft.git
cd libft
make
```
##  License

This project is distributed under the MIT License. See the LICENSE file for details.

## Contact
If you have any questions or feedback, feel free to create an issue on this repository.
