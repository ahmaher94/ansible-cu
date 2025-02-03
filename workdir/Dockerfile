FROM ubuntu
RUN apt update && apt install ssh sudo -y
RUN adduser lol
RUN echo "lol:lol" | chpasswd
RUN sudo usermod -aG sudo lol
ENTRYPOINT service ssh start && bash

# 172.17.0.2