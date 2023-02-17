FROM jenkins/jenkins:lts
# FROM ubuntu:20.04
# if we want to install via apt
USER root
RUN apt-get update && apt-get install -y make && apt-get install -y g++ --fix-missing
# drop back to the regular jenkins user - good practice
USER jenkins
# 9a7cc4d3c92742d5b2f3aa0c2d673fec password