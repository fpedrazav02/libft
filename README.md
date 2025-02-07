<h1 align="center">
	📚 libft
</h1>

<p align="center">
	<b><i>42 School Standard Library</i></b><br>
</p>

<h3 align="center">
	<a href="#%EF%B8%8F-about-the-project">About</a>
	<span> · </span>
	<a href="#%EF%B8%8F-how-to-use-libft">How to use libft</a>
</h3>

---

## 💡 About the project

> _Libft is a custom standard C library designed as part of the 42 School curriculum._

This project provides useful functions that are commonly used in proyects, such as:
- String manipulation
- Memory management
- Linked list operations
- File descriptors handling

---

## 🛠️ How to use libft

### Requirements

In order to use **libft**, you need:
- **`make`** (for compilation)
- **`cc` compiler**
- **Standard C libraries**

### Instructions

**1. Compiling**

To compile **libft**, navigate to the project directory and run:

```sh
make
```

**2. Using the library in your projects**

After compilation, an archive file `libft.a` will be created. You can include it in your project by:

```sh
cc your_program.c $(FLAGS) -o your_program $(OBJECT_FILES) libft.a
```

**3. Cleaning up**

To remove object files, use:
```sh
make clean
```
To remove the compiled library as well, use:
```sh
make fclean
```

---

## 📂 Functions Directory Structure

| Folder       | Functionality |
|-------------|--------------|
| **ft_is/**  | Character checks (`isalnum`, `isalpha`, `isdigit`, etc.) |
| **ft_lst/** | Linked list manipulation (`lstnew`, `lstadd`, `lstclear`, etc.) |
| **ft_mem/** | Memory management (`memset`, `memcpy`, `memmove`, etc.) |
| **ft_printf/** | Custom printf implementation (`ft_printf`, `ft_printnbr`, `ft_printstr`, etc.) |
| **ft_put/** | Writing to file descriptors (`putchar_fd`, `putstr_fd`, etc.) |
| **ft_str/** | String manipulation (`strchr`, `strdup`, `strlen`, `strjoin`, etc.) |
| **ft_to/** | Character conversion (`atoi`, `itoa`, `tolower`, `toupper`) |
| **get_next_line/** | Reading a line from a file descriptor (`get_next_line`) |

---

