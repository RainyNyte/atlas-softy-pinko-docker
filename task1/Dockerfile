FROM ubuntu:latest
RUN apt-get update && apt-get upgrade -y
RUN apt-get install python3 -y
RUN apt-get install python3-pip -y
RUN rm /usr/lib/python*/EXTERNALLY-MANAGED
RUN pip3 install flask
WORKDIR /app
COPY ./api.py .
CMD ["echo", "Hello, World!"]
