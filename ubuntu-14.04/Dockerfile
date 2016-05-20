# This is the Ubuntu 14.04 image for docker-paas.
# Written By: Luke Brady 2016
FROM ubuntu:14.04
MAINTAINER Luke Brady 2016

# Install base packages for use within the \
# container and update the os.
RUN sudo apt-get update && apt-get install -y git vim

# Set metadata for the container.
ENV UBUNTU_VERSION 14.04
ENV UBUNTU_PAAS_VERSION 1.0.0
ENV UBUNTU_PAAS_SHELL bash

# Allows the container to enter in /bin/bash
ENTRYPOINT ["/bin/bash"]

# CMD says hello to the user.
CMD ["printf 'Allo and welcome to Luke Brady's Paas Ubuntu 14.04 image.\n
                                             Have a great time friend\n."]
   
