# ft_printf

ft_printf
The goal of this project is to create a custom ft_printf() function that provides similar functionality to the standard printf() function in C.

The ft_printf() function can be used to print a formatted output string. The function takes in formatting strings that look for specific features in the output string, interprets and handles them correctly.

The project includes the following features:

Implementation of %c, %s, %p, %d, %i, %u, %x, and %X features

Printing % symbol with %%


Usage
The ft_printf() function is compiled and linked with the static library libftprintf.a. The project can be compiled with the make command. After compilation, you can use sample programs in the test.c file.


#include "ft_printf.h"

int main(){

    ft_printf("Hello, %s!\n", "world");
    
    return 0;  
}

Contributing
If you want to contribute to this project, please submit a pull request on the GitHub page. We welcome feedback for any errors or suggestions for improvements in the project.

Thank you!
