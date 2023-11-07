# From Newest Ubuntu Version, Install updates along with python and Flask
# In the /app WD, copy api.py to the server
FROM ubuntu:latest
RUN apt-get update -y
RUN apt-get upgrade -y
RUN apt-get install -y python3 python3-pip
RUN pip3 install Flask
WORKDIR /app
COPY ./api.py /app/api.py
EXPOSE 5252
CMD ["python3", "api.py"]
