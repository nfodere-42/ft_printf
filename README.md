# ft_printf
<img src="images/logo_ft_printf.png" width="512" hegiht="auto">

## Description
ft_printf is a 42 project that aims to replicate the behavior of the original C printf function by implementing a dedicated function for each supported data type.

>[!NOTE]
>This project uses [Libft](https://github.com/nfodere-42/libft)

## Project files
`src/Makefile`: Build automation file for Ft_printf and Libft.

`src/ft_format_chr.c`: Function to write a character when my format_intrp() function detects %c.

`src/ft_format_hex.c`: Function to write a hexadecimal number when my format_intrp() function detects %x or %X.

`src/ft_format_int.c`: Function to write an integer when my format_intrp() function detects %d or %i.

`src/ft_format_prcn.c`: Function to write the '%' character when my format_intrp() function detects %%.

`src/ft_format_ptr.c`: Function to write a pointer when my format_intrp() function detects %p.

`src/ft_format_str.c`: Function to write a string when my format_intrp() function detects %s.

`src/ft_format_usgn_int.c`: Function to write an unsigned integer when my format_intrp() function detects %u.

`src/ft_printf.c`: The entry point of the program.

`src/ft_printf.h`" The header containing the definitions, declarations, and libraries.

### Libft files

`src/libft/ft_atoi.c`: Converts a string to an integer.

`src/libft/ft_bzero.c`: Sets a memory block to zero.

`src/libft/ft_calloc.c`: Allocates zero-initialized memory.

`src/libft/ft_isalnum.c`: Checks if a character is alphanumeric.

`src/libft/ft_isalpha.c`: Checks if a character is alphabetic.

`src/libft/ft_isascii.c`: Checks if a character is a valid ASCII value.

`src/libft/ft_isdigit.c`: Checks if a character is a digit.

`src/libft/ft_isprint.c`: Checks if a character is printable.

`src/libft/ft_itoa.c`: Converts an integer to a string.

`src/libft/ft_memchr.c`: Searches for a byte in a memory block.

`src/libft/ft_memcmp.c`: Compares two memory blocks.

`src/libft/ft_memcpy.c`: Copies memory from one location to another.

`src/libft/ft_memmove.c`: Copies memory safely, even with overlap.

`src/libft/ft_memset.c`: Fills a memory block with a specific byte.

`src/libft/ft_putchar_fd.c`: Writes a character to a file descriptor.

`src/libft/ft_putendl_fd.c`: Writes a string followed by a newline to a file descriptor.

`src/libft/ft_putnbr_fd.c`: Writes an integer to a file descriptor.

`src/libft/ft_putstr_fd.c`: Writes a string to a file descriptor.

`src/libft/ft_split.c`: Splits a string into an array using a delimiter.

`src/libft/ft_strchr.c`: Finds the first occurrence of a character in a string.

`src/libft/ft_strdup.c`: Creates a duplicate of a string.

`src/libft/ft_striteri.c`: Applies a function to each character of a string (with index).

`src/libft/ft_strjoin.c`: Joins two strings into a new one.

`src/libft/ft_strlcat.c`: Appends a string to another with size-bounded safety.

`src/libft/ft_strlcpy.c`: Copies a string with size-bounded safety.

`src/libft/ft_strlen.c`: Returns the length of a string.

`src/libft/ft_strmapi.c`: Creates a new string by applying a function to each character.

`src/libft/ft_strncmp.c`: Compares two strings up to a given length.

`src/libft/ft_strnstr.c`: Searches for a substring within a limited length.

`src/libft/ft_strrchr.c`: Finds the last occurrence of a character in a string.

`src/libft/ft_strtrim.c`: Trims characters from the start and end of a string.

`src/libft/ft_substr.c`: Extracts a substring from a string.

`src/libft/ft_tolower.c`: Converts a character to lowercase.

`src/libft/ft_toupper.c`: Converts a character to uppercase.

`src/libft/libft.h`: The header containing the definitions, declarations, and libraries.

***This project has been created as part of the 42 curriculum by Néo Foderé de Frutos (nfodere-), student at 42 Barcelona***
