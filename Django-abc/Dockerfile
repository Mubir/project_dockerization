# base image
FROM python:3.7
ENV PYTHONUNBUFFERED 1
# creating app folder
# RUN allows to pass command
# this will have entire project
RUN mkdir /app
#set working directory
WORKDIR /app
# requirement file has the sw or evn that need run this project
# need to copy to the working directory
COPY requirements.txt /app/
# install the requirements
RUN pip install -r requirements.txt
# copy files from current to container working dir
COPY . /app/

