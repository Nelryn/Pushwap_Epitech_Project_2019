##
## EPITECH PROJECT, 2020
## Makefile root
## File description:
## my_printf
##

SRC	=	my_put_nbr.c	\
		my_putstr.c	\
		my_putchar.c	\
		percent_cases.c	\
		print_letters.c	\
		my_put_unsigned_nbr.c	\
		my_put_base.c	\
		double_hexas.c	\
		my_printf.c	\
		my_getnbr.c	\

CFLAGS	=	-W -Wall -Wextra -Werror -g -I./includes

NAME	=	libmy.a

OBJ	=	$(SRC:.c=.o)

all: $(OBJ)
	ar rc $(NAME) $(OBJ)

clean:
	rm -f $(OBJ)
	rm -f *~

fclean: clean
	rm -f $(NAME)

re: fclean all
