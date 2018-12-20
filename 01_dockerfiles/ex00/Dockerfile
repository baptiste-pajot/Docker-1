# **************************************************************************** #
#                                                           LE - /             #
#                                                               /              #
#    Dockerfile                                       .::    .:/ .      .::    #
#                                                  +:+:+   +:    +:  +:+:+     #
#    By: bpajot <marvin@le-101.fr>                  +:+   +:    +:    +:+      #
#                                                  #+#   #+    #+    #+#       #
#    Created: 2018/12/20 14:55:26 by bpajot       #+#   ##    ##    #+#        #
#    Updated: 2018/12/20 15:59:40 by bpajot      ###    #+. /#+    ###.fr      #
#                                                          /                   #
#                                                         /                    #
# **************************************************************************** #

FROM alpine

RUN apk update && apk upgrade && apk add vim

ENTRYPOINT vim

# docker build -t ex00 .
# docker run --rm -it ex00 
