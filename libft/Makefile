# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: kenguyen <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2017/11/13 18:11:48 by kenguyen          #+#    #+#              #
#    Updated: 2017/12/05 15:46:23 by adlabban         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a

CLANG = gcc

SRC = ./ft_memset.c \
	  ./ft_bzero.c \
	  ./ft_memcpy.c \
	  ./ft_memmove.c \
	  ./ft_memccpy.c \
	  ./ft_strchr.c \
	  ./ft_memchr.c \
	  ./ft_memcmp.c \
	  ./ft_strcpy.c \
	  ./ft_strdup.c \
	  ./ft_strlen.c \
	  ./ft_strncpy.c \
	  ./ft_strcat.c \
	  ./ft_strncat.c \
	  ./ft_strlcat.c \
	  ./ft_strrchr.c \
	  ./ft_strstr.c \
	  ./ft_strnstr.c \
	  ./ft_strcmp.c \
	  ./ft_strncmp.c \
	  ./ft_atoi.c \
	  ./ft_isalpha.c \
	  ./ft_isdigit.c \
	  ./ft_isalnum.c \
	  ./ft_isascii.c \
	  ./ft_isprint.c \
	  ./ft_toupper.c \
	  ./ft_tolower.c \
	  ./ft_memalloc.c \
	  ./ft_itoa.c \
	  ./ft_memdel.c \
	  ./ft_putchar_fd.c \
	  ./ft_putchar.c \
	  ./ft_putendl_fd.c \
	  ./ft_putendl.c \
	  ./ft_putnbr_fd.c \
	  ./ft_putnbr.c \
	  ./ft_putstr_fd.c \
	  ./ft_putstr.c \
	  ./ft_strclr.c \
	  ./ft_strdel.c \
	  ./ft_strequ.c \
	  ./ft_striter.c \
	  ./ft_striteri.c \
	  ./ft_strjoin.c \
	  ./ft_strmap.c \
	  ./ft_strmapi.c \
	  ./ft_strnequ.c \
	  ./ft_strnew.c \
	  ./ft_strsplit.c \
	  ./ft_strsub.c \
	  ./ft_strtrim.c \
	  ./ft_lstnew.c \
	  ./ft_lstdelone.c \
	  ./ft_lstdel.c \
	  ./ft_lstadd.c \
	  ./ft_lstiter.c \
	  ./ft_lstmap.c \
	  ./ft_lpause.c \
	  ./ft_strrev.c \
	  ./ft_range.c \
	  ./ft_ultimate_range.c \
	  ./ft_recursive_factorial.c

OBJ = $(SRC:.c=.o)

RM = rm -f

FLAG = -Wall -Werror -Wextra

all: $(NAME)

$(NAME):
	$(CLANG) -c $(FLAG) $(SRC) -I .
	ar rc $(NAME) $(OBJ)
	ranlib $(NAME)

clean:
	$(RM) $(OBJ)

fclean: clean
	$(RM) $(NAME)

re: fclean all
