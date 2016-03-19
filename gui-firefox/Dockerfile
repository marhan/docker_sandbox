FROM ubuntu:14.04
RUN apt-get update
RUN apt-get install -y firefox
RUN groupadd -g GID markus
RUN useradd -d /home/markus -s /bin/bash -m dockerinpractice -u UID -g GID
USER markus
ENV HOME /home/markus
CMD /usr/bin/firefox
