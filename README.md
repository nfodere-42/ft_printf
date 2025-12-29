# Ft_printf
![](images/logo_ft_printf.png)

## Description
Ft_printf is a 42 project that aims to replicate the behavior of the original C printf function by implementing a dedicated function for each supported data type.
>[!NOTE]
>This project uses [Libft](https://github.com/nfodere-42/libft)

## Project files
`src/Makefile`: Build automation file.

`src/ft_format_chr.c`: Function to write a character when my format_intrp() function detects %c.

`src/ft_format_hex.c`: Function to write a hexadecimal number when my format_intrp() function detects %x or %X.

`src/ft_format_int.c`: Function to write an integer when my format_intrp() function detects %d or %i.

`src/ft_format_prcn.c`: Function to write the '%' character when my format_intrp() function detects %%.

`src/ft_format_ptr.c`: Function to write a pointer when my format_intrp() function detects %p.

`src/ft_format_str.c`: Function to write a string when my format_intrp() function detects %s.

`src/ft_format_usgn_int.c`: Function to write an unsigned integer when my format_intrp() function detects %u.

`src/ft_printf.c`: The entry point of the program.

`src/ft_printf.h`" The header containing the definitions, declarations, and libraries.

***This project has been created as part of the 42 curriculum by Néo Foderé de Frutos (nfodere-), a student at 42 Barcelona***
