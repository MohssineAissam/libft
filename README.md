# Libft - Your First C Library

![42 School Logo](https://img.shields.io/badge/42/1337-BornToCode-black?style=for-the-badge&logo=42)

**My first steps into C programming.** This project is the first assignment of the 42/1337 common core curriculum. The goal is to recreate a set of standard C library functions, as well as some additional utility functions, which will be used in all my future C projects.

---

## 📚 Table of Contents

* [About the Project](#about-the-PROJECT)
* [Functions Implemented](#functions-implemented)
* [How to Use](#how-to-use)
* [Author](#author)

---

## 🎯 About the Project

`libft` is a fundamental project that teaches the basics of C, function implementation, and library creation. It's divided into three main parts:

1.  **Part 1: Libc Functions** - Recreating standard functions from libraries like `<string.h>`, `<stdlib.h>`, and `<ctype.h>`.
2.  **Part 2: Additional Functions** - Creating new, useful functions that are not in the standard C library, such as `ft_split` (splitting a string by a delimiter) and `ft_itoa` (integer to ASCII string).
3.  **Bonus Part: Linked List Functions** - Implementing a set of functions to create and manage a simple linked list.

---

## 🛠 Functions Implemented

Here is a list of the functions you will find in this library.

### Part 1: Libc Functions (from `<ctype.h>`, `<string.h>`, `<stdlib.h>`)

| Function | Description |
| :--- | :--- |
| `ft_isalpha` | Checks for an alphabetic character. |
| `ft_isdigit` | Checks for a digit (0-9). |
| `ft_isalnum` | Checks for an alphanumeric character. |
| `ft_isascii` | Checks for a valid ASCII character. |
| `ft_isprint` | Checks for any printable character. |
| `ft_strlen` | Calculates the length of a string. |
| `ft_memset` | Fills memory with a constant byte. |
| `ft_bzero` | Writes zeroes to a byte string. |
| `ft_memcpy` | Copies a memory area. |
| `ft_memmove` | Copies a memory area (safe for overlap). |
| `ft_strlcpy` | Size-bounded string copying. |
| `ft_strlcat` | Size-bounded string concatenation. |
| `ft_toupper` | Converts lowercase to uppercase. |
| `ft_tolower` | Converts uppercase to lowercase. |
| `ft_strchr` | Locates the first occurrence of a character in a string. |
| `ft_strrchr` | Locates the last occurrence of a character in a string. |
| `ft_strncmp` | Compares two strings (up to n characters). |
| `ft_memchr` | Scans memory for a character. |
| `ft_memcmp` | Compares two memory areas. |
| `ft_strnstr` | Locates a substring in a string (up to n characters). |
| `ft_atoi` | Converts an ASCII string to an integer. |
| `ft_calloc` | Allocates and zeroes memory. |
| `ft_strdup` | Duplicates a string. |

### Part 2: Additional Functions

| Function | Description |
| :--- | :--- |
| `ft_substr` | Returns a new string from a substring. |
| `ft_strjoin` | Concatenates two strings into a new string. |
| `ft_strtrim` | Trims specified characters from the start and end of a string. |
| `ft_split` | Splits a string into an array of strings using a delimiter. |
| `ft_itoa` | Converts an integer to an ASCII string. |
| `ft_strmapi` | Applies a function to each character of a string. |
| `ft_striteri` | Applies a function to each character of a string (with index). |
| `ft_putchar_fd` | Outputs a character to a file descriptor. |
| `ft_putstr_fd` | Outputs a string to a file descriptor. |
| `ft_putendl_fd` | Outputs a string to a file descriptor, followed by a newline. |
| `ft_putnbr_fd` | Outputs an integer to a file descriptor. |



---

## 🚀 How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/MohssineAissam/libft.git
cd libft
