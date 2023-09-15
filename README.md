<center>
<h1 style="display: inline-block; border-bottom: none; margin-right: 20px;">42cursus - Libft</h1>
<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/wengcychan/42cursus-libft?style=plastic&color=blue&label=C%20language&logo=42" />
</center>

<div style="border-bottom: 2px solid grey; margin-bottom: 20px;"></div>

Libft is a project designed to create and utilize a custom C library known as `libft`.

For more projects related to 42cursus, please visit the hive-42cursus repository.

## Introduction

The goal of this project is to understand the inner workings of fundamental C Standard Library functions, implement them, and become proficient in their usage. The project is divided into three main parts:

### Part 1: Redoing Standard Library Functions

The first part is to recreate a set of functions from the C Standard Library, which includes:

- **[ft_isalph](./ft_isalpha.c)**
- **[ft_isdigit](./ft_isdigit.c)**
- **[ft_isalnum](./ft_isalnum.c)**
- **[ft_isascii](./ft_isascii.c)**
- **[ft_isprint](./ft_isprint.c)**
- **[ft_strlen](./ft_strlen.c)**
- **[ft_memset](./ft_memset.c)**
- **[ft_bzero](./ft_bzero.c)**
- **[ft_memcpy](./ft_memcpy.c)**
- **[ft_memmove](./ft_memmove.c)**
- **[ft_strlcpy](./ft_strlcpy.c)**
- **[ft_strlcat](./ft_strlcat.c)**
- **[ft_toupper](./ft_toupper.c)**
- **[ft_tolower](./ft_tolower.c)**
- **[ft_strchr](./ft_strchr.c)**
- **[ft_strrchr](./ft_strrchr.c)**
- **[ft_strncmp](./ft_strncmp.c)**
- **[ft_memchr](./ft_memchr.c)**
- **[ft_memcmp](./ft_memcmp.c)**
- **[ft_strnstr](./ft_strnstr.c)**
- **[ft_atoi](./ft_atoi.c)**
- **[ft_calloc](./ft_calloc.c)**
- **[ft_strdup](./ft_strdup.c)**

### Part 2: Adding New Functions

The second part is to develop a set of functions that either do not exist in the C Standard Library or have a different form. These functions include:

- **[ft_substr](./ft_substr.c)**
- **[ft_strjoin](./ft_strjoin.c)**
- **[ft_strtrim](./ft_strtrim.c)**
- **[ft_split](./ft_split.c)**
- **[ft_itoa](./ft_itoa.c)**
- **[ft_strmapi](./ft_strmapi.c)**
- **[ft_striteri](./ft_striteri.c)**
- **[ft_putchar_fd](./ft_putchar_fd.c)**
- **[ft_putstr_fd](./ft_putstr_fd.c)**
- **[ft_putendl_fd](./ft_putendl_fd.c)**
- **[ft_putnbr_fd](./ft_putnbr_fd.c)**

### Bonus Part: Linked List Functions

The bonus part focuses on working with linked lists and includes the following functions:

- **[ft_lstnew](./ft_lstnew_bonus.c)**
- **[ft_lstadd_front](./ft_lstadd_front_bonus.c)**
- **[ft_lstsize](./ft_lstsize_bonus.c)**
- **[ft_lstlast](./ft_lstlast_bonus.c)**
- **[ft_lstadd_back](./ft_lstadd_back_bonus.c)**
- **[ft_lstdelone](./ft_lstdelone_bonus.c)**
- **[ft_lstclear](./ft_lstclear_bonus.c)**
- **[ft_lstiter](./ft_lstiter_bonus.c)**
- **[ft_lstmap](./ft_lstmap_bonus.c)**

## Usage

To use the `libft` library in C projects, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/wengcychan/42cursus-libft.git
	```

2. Compile the library for Part 1 and Part 2:

   ```bash
	make
	```
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; This will generate a library file named `libft.a`.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Additionally, running `make bonus` will add the functions from the bonus part to the `libft.a` library.


3. In your C projects, include the header file `libft.h`:

	```c
	#include "libft.h"
	```

4. Compile your C program with the `libft.a` library:

   ```bash
	gcc myprogram.c -L. -lft
	```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Replace `myprogram.c` with your source code file.
