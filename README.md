# ♻️ Libft ♻️

`Compilation of simple functions`



### Useful ressources

**📚 [`GITBOOK`](https://42-cursus.gitbook.io/guide/rank-00/libft) 📚** - Gitbook for libft

**🧪 [`FRANCINETTE`](https://github.com/xicodomingues/francinette) 🧪** - Testing

## 

### Existing functions

- [`ft_isalpha`](ft_isalpha.c) - check if letter
- [`ft_isdigit`](ft_isdigit.c) - check if number
- [`ft_isalnum`](ft_isalnum.c) - check if alphanumerical
- [`ft_isascii`](ft_isascii.c) - check if ASCII
- [`ft_isprint`](ft_isprint.c) - check if printable
- [`ft_strlen`](ft_strlen.c) - returns string length
- [`ft_memset`](ft_memset.c) - changes given memory to given character
- [`ft_bzero`](ft_bzero.c) - nulls given memory
- [`ft_memcpy`](ft_memcpy.c)	- copies given memory
- [`ft_memmove`](ft_memmove.c) - copies given memory in a non-destructive manner (see [gitbook](https://42-cursus.gitbook.io/guide/rank-00/libft/libc-functions/ft_memmove))
- [`ft_strlcpy`](ft_strlcpy.c)	- copies a string in another
- [`ft_strlcat`](ft_strlcat.c) - concatenates a string to another
- [`ft_toupper`](ft_toupper.c)	- converts lowercase letters to upper
- [`ft_tolower`](ft_tolower.c) - converts upperrcase letters to lower
- [`ft_strchr`](ft_strchr.c)	- finds the first occurence of a character in a string
- [`ft_strrchr`](ft_strrchr.c)	- finds the last occurence of a character in a string
- [`ft_strncmp`](ft_strncmp.c) - compares two strings
- [`ft_memchr`](ft_memchr.c)	- finds the first occurence of a character in memory
- [`ft_memcmp`](ft_memcmp.c) - compares two bits of memory
- [`ft_strnstr`](ft_strnstr.c) - finds a string in a string
- [`ft_atoi`](ft_atoi.c) - converts a string in an integer
- [`ft_calloc`](ft_calloc.c) - allocates memory and nulls it
- [`ft_strdup`](ft_strdup.c) - duplicates a string

### New functions

- [`ft_substr`](ft_substr.c)	- returns part of a string
- [`ft_strjoin`](ft_strjoin.c)	- creates a new string from a concatenation of two strings
- [`ft_strtrim`](ft_strtrim.c)	- removes given characters form a string
- [`ft_split`](ft_split.c)	- splits a string using a character
- [`ft_itoa`](ft_itoa.c)	- converts an integer to a string
- [`ft_strmapi`](ft_strmapi.c)	- creates a string by passing each character of a given string through a function
- [`ft_striteri`](ft_striteri.c)	- modifies a string by passing each character of a given string through a function
- [`ft_putchar_fd`](ft_putchar_fd.c)	- writes a character on fd
- [`ft_putstr_fd`](ft_putstr_fd.c)	- writes a string on fd
- [`ft_putendl_fd`](ft_putendl_fd.c)	- writes a string on fd with a newline
- [`ft_putnbr_fd`](ft_putnbr_fd.c) - writes a number on fd

### Bonus functions (linked lists)

- [`ft_lstnew`](ft_lstnew.c)	- creates a new node
- [`ft_lstadd_front`](ft_lstadd_front.c)	- adds a node at the start
- [`ft_lstsize`](ft_lstsize.c)	- counts the nodes
- [`ft_lstlast`](ft_lstlast.c)	- returns the last node
- [`ft_lstadd_back`](ft_lstadd_back.c)	- adds a node at the end
- [`ft_lstdelone`](ft_lstdelone.c)	- deletes a node
- [`ft_lstclear`](ft_lstclear.c)	- deletes a list
- [`ft_lstiter`](ft_lstiter.c)	- modifies a list by passing each of its nodes through a function
- [`ft_lstmap`](ft_lstmap.c) - creates a list by passing each node of a list through a function



