# 42_libft

## Purpose
> This project involves creating the libft library, a collection of custom C functions designed to replicate and extend standard libc functionalities. The library includes implementations for string manipulation, memory allocation, linked list management, and other utility functions. These functions are carefully re-coded to provide reusable tools for future 42 projects and other programming endeavors.

## Files

### Makefile
- tbd

### Header
- tbd

### Source Code
| No  | Libc Functions                                                                 |   | No  | Additional Functions                                                                 |   | No  | (in progress) Bonus Functions                                                                          |
| :-: | :----------------------------------------------------------------------------- | - | :-: | :----------------------------------------------------------------------------------- | - | :-: | :--------------------------------------------------------------------------------------- |
| 1   | [ft_memset]   |   | 1   | [ft_substr]         |   | 1   | [ft_lstnew]             |
| 2   | [ft_bzero]    |   | 2   | [ft_strjoin]      |   | 2   | [ft_lstadd_front] |
| 3   | [ft_memcpy]   |   | 3   | [ft_strtrim]      |   | 3   | [ft_lstsize]           |
| 4   | [ft_memcpy] |   | 4   | [ft_split]           |   | 4   | [ft_lstlast]           |
| 5   | [ft_memmove] |   | 5   | [ft_itoa]             |   | 5   | [ft_lstadd_back]   |
| 6   | [ft_memchr]   |   | 6   | [ft_strmapi]      |   | 6   | [ft_lstdelone]      |
| 7   | [ft_memcmp]   |   | 7   | [ft_putchar_fd] |   | 7   | [ft_lstclear]         |
| 8   | [ft_strlen]   |   | 8   | [ft_putstr_fd]   |   | 8   | [ft_lstiter]          |
| 9   | [ft_strlcpy] |   | 9   | [ft_putendl_fd] |   | 9   | [ft_lstmap]             |
| 10  | [ft_strlcat] |   | 10  | [ft_putnbr_fd]   |   |     |                                                                                          |
| 11  | [ft_strchr]   |   | 11   | [ft_striteri]                                                                                   |   |     |                                                                                          |
| 12  | [ft_strrchr] |   |     |                                                                                      |   |     |                                                                                          |
| 13  | [ft_strnstr] |   |     |                                                                                      |   |     |                                                                                          |
| 14  | [ft_strncmp] |   |     |                                                                                      |   |     |                                                                                          |
| 15  | [ft_atoi]       |   |     |                                                                                      |   |     |                                                                                          |
| 16  | [ft_isalpha] |   |     |                                                                                      |   |     |                                                                                          |
| 17  | [ft_isdigit] |   |     |                                                                                      |   |     |                                                                                          |
| 18  | [ft_isalnum] |   |     |                                                                                      |   |     |                                                                                          |
| 19  | [ft_isascii] |   |     |                                                                                      |   |     |                                                                                          |
| 20  | [ft_isprint] |   |     |                                                                                      |   |     |                                                                                          |
| 21  | [ft_toupper] |   |     |                                                                                      |   |     |                                                                                          |
| 22  | [ft_tolower] |   |     |                                                                                      |   |     |                                                                                          |
| 23  | [ft_calloc]   |   |     |                                                                                      |   |     |                                                                                          |
| 24  | [ft_strdup]  |   |     |                                                                                      |   |     |    |

## Instructions
To compile the code, run `make` in the terminal. This will create a library called `libft.a`.

To clean the object files and library, run `make clean` and `make fclean`, respectively.

The library is accompanied by a header file called libft.h, which contains prototypes for all the functions in the library. To use the library in your project, include the header file and link to the library as described above.

## Grade: 125 / 100

## Used Tests
- Francinette: https://github.com/xicodomingues/francinette
- libftTester: https://github.com/Tripouille/libftTester
