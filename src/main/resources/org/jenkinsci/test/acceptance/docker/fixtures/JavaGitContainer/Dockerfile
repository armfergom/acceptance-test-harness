# Adds Java tooling to the git container so that this docker image can be used as agent as well

FROM jenkins/git:3e22c64d038a

RUN apt-get update -y && apt-get install --no-install-recommends -y software-properties-common

RUN add-apt-repository ppa:openjdk-r/ppa
RUN apt-get update
RUN apt-get install --no-install-recommends -y \
    openjdk-8-jdk
