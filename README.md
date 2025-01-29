# ft_printf
ft_printf is a custom implementation of the standard `printf` function in C. This project, part of 42's Common Core, teaches formatted output handling, variadic functions, and low-level memory management.

This project deepened my understanding of how printf() works under the hood.

## 🚀 Features  
- Supports basic format specifiers: `%c`, `%s`, `%p`, `%d`, `%i`, `%u`, `%x`, `%X`
- Uses variadic arguments (`va_list`) 

## 🔧 Usage  
1. **Include at the bottom of 'ft_ptintf.c'**:
```c
int main()
{
    ft_printf("Hello, %s!\n", "world"); // or any other supported format specifiers.
    return (0);
}
```
2. **Compile the program**:  
```bash
make
```

3. **Run the program**:
```bash
./ft_printf
```
