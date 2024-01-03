# ♻️ Libft ♻️

`ca za tout libft pour le 42 ouioui`



### Resources utiles

**📚 [`GITBOOK`](https://42-cursus.gitbook.io/guide/rank-00/libft) 📚** - Gitbook pour libft

**🧪 [`FRANCINETTE`](https://github.com/xicodomingues/francinette) 🧪** - Si la francinette elle passe, alors c'est nickel

## 

### Fonctions existantes

- [`ft_isalpha`](ft_isalpha.c) - est-ce une lettre ?
- [`ft_isdigit`](ft_isdigit.c) - est-ce un chiffre ?
- [`ft_isalnum`](ft_isalnum.c) - est-ce une lettre ou un chiffre ?
- [`ft_isascii`](ft_isascii.c) - est-ce compris dans ASCII ?
- [`ft_isprint`](ft_isprint.c) - est-ce imprimable ?
- [`ft_strlen`](ft_strlen.c) - longueur d'une string
- [`ft_memset`](ft_memset.c) - remplir une certaine mémoire avec un certain caractère (octet)
- [`ft_bzero`](ft_bzero.c) - remplire une certaine mémoire avec des octets nuls
- [`ft_memcpy`](ft_memcpy.c)	- copie un bout de mémoire
- [`ft_memmove`](ft_memmove.c) - copie un bout de mémoire de façon non-destructive (voir [gitbook](https://42-cursus.gitbook.io/guide/rank-00/libft/libc-functions/ft_memmove) il est bizarre celui-ci)
- [`ft_strlcpy`](ft_strlcpy.c)	- copie une string dans une autre
- [`ft_strlcat`](ft_strlcat.c) - concatène une string à une autre
- [`ft_toupper`](ft_toupper.c)	- convertis une minuscule en majscule
- [`ft_tolower`](ft_tolower.c) - devine
- [`ft_strchr`](ft_strchr.c)	- trouve la première occurrence d'un caractère dans une string
- [`ft_strrchr`](ft_strrchr.c)	- trouve la dernière occurrence d'un caractère dans une string
- [`ft_strncmp`](ft_strncmp.c) - compare deux strings
- [`ft_memchr`](ft_memchr.c)	- trouve la première occurrence d'un caractère dans un bout de mémoire
- [`ft_memcmp`](ft_memcmp.c) - compare deux morceaux de mémoire
- [`ft_strnstr`](ft_strnstr.c) - trouve une string dans une string
- [`ft_atoi`](ft_atoi.c) - convertis une string en un int
- [`ft_calloc`](ft_calloc.c) - alloue de la mémoire en la remplissant de zéros
- [`ft_strdup`](ft_strdup.c) - duplique une string

### Fonctions inédites

- [`ft_substr`](ft_substr.c)	- retourne une partie d'une string
- [`ft_strjoin`](ft_strjoin.c)	- crée une string avec deux autres
- [`ft_strtrim`](ft_strtrim.c)	- retire certains caractères du début et de la fin d'une string
- [`ft_split`](ft_split.c)	- découpe une string en fonction d'un caractère
- [`ft_itoa`](ft_itoa.c)	- convertis un int en string
- [`ft_strmapi`](ft_strmapi.c)	- crée une string en appliquant une fonction à chaque caractère d'une autre string
- [`ft_striteri`](ft_striteri.c)	- modifie une string en appliquant une fonction à chacun de ses caractères
- [`ft_putchar_fd`](ft_putchar_fd.c)	- imprime un caractère dans le fd
- [`ft_putstr_fd`](ft_putstr_fd.c)	- imprime une string dans le fd
- [`ft_putendl_fd`](ft_putendl_fd.c)	- imprime une string avec un retour à la ligne dans le fd
- [`ft_putnbr_fd`](ft_putnbr_fd.c) - imprime un nombre dans le fd

### Fonctions bonus (listes chaînées)

- [`ft_lstnew`](ft_lstnew.c)	- crées une nouvelle node
- [`ft_lstadd_front`](ft_lstadd_front.c)	- ajoute une node au début d'une liste
- [`ft_lstsize`](ft_lstsize.c)	- nombre de nodes dans la liste
- [`ft_lstlast`](ft_lstlast.c)	- trouve la dernière node de la liste
- [`ft_lstadd_back`](ft_lstadd_back.c)	- ajoute une node à la fin d'une liste
- [`ft_lstdelone`](ft_lstdelone.c)	- supprime et free une node
- [`ft_lstclear`](ft_lstclear.c)	- supprime et free une liste
- [`ft_lstiter`](ft_lstiter.c)	- modifie une liste en lui appliquant une fonction à chacune de ses nodes
- [`ft_lstmap`](ft_lstmap.c) - crée une liste en appliquant une fonction à chaque node d'une autre liste



