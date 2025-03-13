# 42_libft

## Purpose
> This project involves creating the libft library, a collection of custom C functions designed to replicate and extend standard libc functionalities. The library includes implementations for string manipulation, memory allocation, linked list management, and other utility functions. These functions are carefully re-coded to provide reusable tools for future 42 projects and other programming endeavors.

## Files

### Makefile
The `Makefile` is an essential part of the Libft project, responsible for automating the compilation process. It compiles the source files into the required library `libft.a` using the `cc` compiler with the flags `-Wall`, `-Werror`, and `-Wextra`, as specified in the subject. It must include the mandatory rules `$(NAME)`, `all`, `clean`, `fclean`, and `re`, and optionally a bonus rule for compiling the bonus functions separately. This ensures efficient building, cleaning, and rebuilding of the project while adhering to the project’s technical requirements.

Makefile: [Makefile](https://github.com/JohnHapke/42_Lvl0_libft/blob/main/libft/Makefile)

### Header
The header file `libft.h` serves as the central component of the Libft project, declaring all the function prototypes required for the library. It ensures that the mandatory libc functions, additional utility functions, and bonus list manipulation functions are properly defined and accessible for use throughout the project. Additionally, it includes the structure definition for linked lists (e.g., t_list) used in the bonus part, making it a crucial file for maintaining consistency and organization in the library.

Header File: [libft.h](https://github.com/JohnHapke/42_Lvl0_libft/blob/main/libft/libft.h)

### Source Code
| No. | Function          | Description                                                              | Link                                           |
|-----|-------------------|--------------------------------------------------------------------------|------------------------------------------------|
| 1   | ft_isalpha        | Checks if a character is a letter                                        | [ft_isalpha.c](libft/ft_isalpha.c)            |
| 2   | ft_isdigit        | Checks if a character is a digit                                         | [ft_isdigit.c](libft/ft_isdigit.c)            |
| 3   | ft_isalnum        | Checks if a character is alphanumeric                                    | [ft_isalnum.c](libft/ft_isalnum.c)            |
| 4   | ft_isascii        | Checks if a character is in the ASCII range                              | [ft_isascii.c](libft/ft_isascii.c)            |
| 5   | ft_isprint        | Checks if a character is printable                                       | [ft_isprint.c](libft/ft_isprint.c)            |
| 6   | ft_strlen         | Calculates the length of a string                                        | [ft_strlen.c](libft/ft_strlen.c)              |
| 7   | ft_memset         | Fills a memory area with a specified character                           | [ft_memset.c](libft/ft_memset.c)              |
| 8   | ft_bzero          | Sets a memory area to zero                                               | [ft_bzero.c](libft/ft_bzero.c)                |
| 9   | ft_memcpy         | Copies data from one memory area to another                              | [ft_memcpy.c](libft/ft_memcpy.c)              |
| 10  | ft_memmove        | Copies data with overlap handling                                        | [ft_memmove.c](libft/ft_memmove.c)            |
| 11  | ft_strlcpy        | Copies a string with a length limit                                      | [ft_strlcpy.c](libft/ft_strlcpy.c)            |
| 12  | ft_strlcat        | Concatenates two strings with a length limit                             | [ft_strlcat.c](libft/ft_strlcat.c)            |
| 13  | ft_toupper        | Converts a character to uppercase                                        | [ft_toupper.c](libft/ft_toupper.c)            |
| 14  | ft_tolower        | Converts a character to lowercase                                        | [ft_tolower.c](libft/ft_tolower.c)            |
| 15  | ft_strchr         | Finds the first occurrence of a character in a string                    | [ft_strchr.c](libft/ft_strchr.c)              |
| 16  | ft_strrchr        | Finds the last occurrence of a character in a string                     | [ft_strrchr.c](libft/ft_strrchr.c)            |
| 17  | ft_strncmp        | Compares two strings up to a specified length                            | [ft_strncmp.c](libft/ft_strncmp.c)            |
| 18  | ft_memchr         | Searches for a character in a memory area                                | [ft_memchr.c](libft/ft_memchr.c)              |
| 19  | ft_memcmp         | Compares two memory areas                                                | [ft_memcmp.c](libft/ft_memcmp.c)              |
| 20  | ft_strnstr        | Searches for a substring in a string with a length limit                 | [ft_strnstr.c](libft/ft_strnstr.c)            |
| 21  | ft_atoi           | Converts a string to an integer                                          | [ft_atoi.c](libft/ft_atoi.c)                  |
| 22  | ft_calloc         | Allocates memory and initializes it to zero                              | [ft_calloc.c](libft/ft_calloc.c)              |
| 23  | ft_strdup         | Duplicates a string                                                      | [ft_strdup.c](libft/ft_strdup.c)              |
| 24  | ft_substr         | Creates a substring from a string                                        | [ft_substr.c](libft/ft_substr.c)              |
| 25  | ft_strjoin        | Concatenates two strings                                                 | [ft_strjoin.c](libft/ft_strjoin.c)            |
| 26  | ft_strtrim        | Removes characters from the beginning and end of a string                | [ft_strtrim.c](libft/ft_strtrim.c)            |
| 27  | ft_split          | Splits a string into an array based on a delimiter                       | [ft_split.c](libft/ft_split.c)                |
| 28  | ft_itoa           | Converts an integer to a string                                          | [ft_itoa.c](libft/ft_itoa.c)                  |
| 29  | ft_strmapi        | Applies a function to each character of a string                         | [ft_strmapi.c](libft/ft_strmapi.c)            |
| 30  | ft_striteri       | Applies a function to each character of a string with its index          | [ft_striteri.c](libft/ft_striteri.c)          |
| 31  | ft_putchar_fd     | Writes a character to a file descriptor                                  | [ft_putchar_fd.c](libft/ft_putchar_fd.c)      |
| 32  | ft_putstr_fd      | Writes a string to a file descriptor                                     | [ft_putstr_fd.c](libft/ft_putstr_fd.c)        |
| 33  | ft_putendl_fd     | Writes a string followed by a newline to a file descriptor               | [ft_putendl_fd.c](libft/ft_putendl_fd.c)      |
| 34  | ft_putnbr_fd      | Writes an integer to a file descriptor                                   | [ft_putnbr_fd.c](libft/ft_putnbr_fd.c)        |
| 35  | ft_lstnew         | Creates a new list node                                                  | [ft_lstnew.c](libft/ft_lstnew.c)              |
| 36  | ft_lstadd_front   | Adds a node to the front of a list                                       | [ft_lstadd_front.c](libft/ft_lstadd_front.c)  |
| 37  | ft_lstsize        | Calculates the length of a list                                          | [ft_lstsize.c](libft/ft_lstsize.c)            |
| 38  | ft_lstlast        | Returns the last node of a list                                          | [ft_lstlast.c](libft/ft_lstlast.c)            |
| 39  | ft_lstadd_back    | Adds a node to the end of a list                                         | [ft_lstadd_back.c](libft/ft_lstadd_back.c)    |
| 40  | ft_lstdelone      | Deletes a single list node                                               | [ft_lstdelone.c](libft/ft_lstdelone.c)        |
| 41  | ft_lstclear       | Deletes an entire list                                                   | [ft_lstclear.c](libft/ft_lstclear.c)          |
| 42  | ft_lstiter        | Applies a function to each node of a list                                | [ft_lstiter.c](libft/ft_lstiter.c)            |
| 43  | ft_lstmap         | Creates a new list by applying a function to each node                   | [ft_lstmap.c](libft/ft_lstmap.c)              |
## Instructions
To compile the code, run `make` in the terminal. This will create a library called `libft.a`.

To clean the object files and library, run `make clean` and `make fclean`, respectively.

The library is accompanied by a header file called libft.h, which contains prototypes for all the functions in the library. To use the library in your project, include the header file and link to the library as described above.

## Grade: 125 / 100

## Used Tests
- Francinette: https://github.com/xicodomingues/francinette
- libftTester: https://github.com/Tripouille/libftTester
