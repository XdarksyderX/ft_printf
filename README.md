
# ft_printf

## Overview
`ft_printf` is a custom implementation of the classic `printf` function in C. It's designed to mimic the original `printf` functionality along with additional features. This project is part of the advanced programming segment, helping students deepen their understanding of variadic functions, string processing, and more intricate aspects of C programming.

## Features
- Custom implementation of `printf` supporting multiple format specifiers.
- Additional handlers for various data types like char, string, integers, unsigned, pointers, and hexadecimal formats.
- Utility functions for supporting tasks like counting, spacing, and formatted output.

## Compilation and Usage
### Requirements
- GCC compiler
- GNU make

### Compiling the Library
To compile `ft_printf`, run the following command:

```
make all
```

This compiles the `libftprintf.a` library. The process involves compiling the `libft` library, copying it, and then compiling the `ft_printf` specific files.

### Clean and Recompile
To clean object files and recompile:

```
make re
```

For cleaning up all compiled files:

```
make fclean
```

## File Structure
- `src/*.c` and `src/*/*.c` - Source files for `ft_printf` and its utilities.
- `includes/*.h` - Header files with function prototypes and necessary includes.

## Integration
To integrate `ft_printf` into your C project, include the `libftprintf.a` library and the associated header files in your compilation command.
