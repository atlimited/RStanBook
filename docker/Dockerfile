FROM ubuntu:16.04

RUN apt-get -y update
RUN apt-get -y install python3
RUN apt-get -y install python3-pip
RUN apt-get -y install python3-tk
RUN pip3 install --upgrade pip
RUN pip3 install pystan
RUN pip3 install jupyter
RUN pip3 install pandas
RUN pip3 install matplotlib
RUN pip3 install xlrd
RUN pip3 install scipy
RUN pip3 install seaborn
WORKDIR /home

EXPOSE 8888
