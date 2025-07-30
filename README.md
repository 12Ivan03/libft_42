# Project title 
libft

---

# Libft
A foundational C library re-implementing key standard functions for memory, string, character, and linked list operations — built entirely from scratch as part of the 42 Codam curriculum.

---

## Table of Contents
- [Overview](#-overview)
- [Features](#-Features)
- [Installation](#-Installation)
- [Implementation](#-Implementation)

---

## Overview
This project is a personal reimplementation of the C standard library. It was developed in a restricted environment (no external libraries, limited functions) and demonstrates low-level programming skills including:

- Memory manipulation
- String parsing
- Pointer arithmetic
- Linked list - Custom data structures

---

## Features

### ✅ Implemented Categories:

#### 🧠 Memory Functions
- `ft_memset`, `ft_memcpy`, `ft_memmove`, `ft_bzero`, `ft_calloc`, `ft_memcmp`, `ft_memchr`

#### 🔤 String Functions
- `ft_strlen`, `ft_strdup`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strlcpy`, `ft_strlcat`, `ft_strnstr`, `ft_strjoin`, `ft_substr`, `ft_strtrim`, `ft_split`

#### 🔠 Character Check & Conversion
- `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`, `ft_toupper`, `ft_tolower`

#### 🔢 Conversion
- `ft_atoi`, `ft_itoa`

#### 📁 File Descriptor Output
- `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

#### 🔗 Bonus: Linked List Utilities
- `ft_lstnew`, `ft_lstadd_front`, `ft_lstadd_back`, `ft_lstlast`, `ft_lstsize`
- `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`


---

## Installation

```bash
git clone https://github.com/yourusername/libft.git
cd libft
make 
```

---

## Implementation example

compilation 
  cc -Wall -Wextra -Werror main.c libft.a
  ./a.out


```c
#include "libft.h"
#include <stdop.h>

int  main() {
  char *original = "Codam";
  char *copy = ft_strdup(original);
  
  printf("Original: %s\nCopy: %s \n", original, copy);
  free(copy);
  
  return 0;
}
```
---
