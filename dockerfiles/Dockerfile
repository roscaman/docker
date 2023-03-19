FROM ubuntu
MAINTAINER Roscaman <roscaman@somewhere.net>


# Skip prompts
ARG DEBIAN_FRONTEND=noninteractive


# Update packages
RUN apt update; apt dist-upgrade -y


# Install packages
RUN apt install -y tree vim-nox


# Set entrypoint
ENTRYPOINT <service_name> -D FOREGROUND
