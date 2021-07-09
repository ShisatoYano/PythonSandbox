FROM python:3.9.6-buster

RUN apt -y update
RUN apt -y upgrade

# setting git
RUN apt -y install git
RUN git config --global user.name Shisato
RUN git config --global user.email shisatoyano@gmail.com

# gui
RUN apt -y install libgl1-mesa-dev xorg-dev
RUN apt -y install x11-apps

# display setting
# x server should be working in advance on host pc
ENV DISPLAY=host.docker.internal:0.0

# not to use shared memory
ENV QT_X11_NO_MITSHM=1