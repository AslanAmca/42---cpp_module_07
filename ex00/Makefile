# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: aaslan <aaslan@student.42kocaeli.com.tr    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2023/11/19 12:33:21 by aaslan            #+#    #+#              #
#    Updated: 2023/12/21 14:25:21 by aaslan           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME		:= functions
CXX			:= c++
CXXFLAGS	:= -Wall -Wextra -Werror -std=c++98
SRC			:= main.cpp

all: $(NAME)

$(NAME):
	@$(CXX) $(CXXFLAGS) $(SRC) -o $(NAME)

clean:
	@rm -rf $(NAME)
	@clear

fclean: clean

re: fclean all

.PHONY: all clean fclean re