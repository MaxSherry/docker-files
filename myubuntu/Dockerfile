FROM ubuntu:latest

RUN apt update
RUN apt install -y iputils-ping  telnet git wget curl vim

ADD https://raw.githubusercontent.com/encody/nvim/master/colors/molokai.vim /usr/share/vim/vim80/colors/
ADD .vimrc /root/

# 安装 en_US.UTF-8 并配置环境
ENV LANG C.UTF-8
ENV LANGUAGE C.UTF-8
ENV LC_ALL C.UTF-8