FROM ubuntu:latest
MAINTAINER ema95iv

RUN apt-get update -y
RUN apt-get install -y python-pip python-dev build-essential 

WORKDIR /app
ADD . /app

RUN pip install -r requirements.txt
EXPOSE 5000
ENTRYPOINT ["python"]
CMD ["hello-world.py"]
