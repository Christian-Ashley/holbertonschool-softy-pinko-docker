FROM ubuntu:latest 
RUN apt-get update && apt-get upgrade -y python3 python3-pip
RUN pip3 install Flask
RUN pip3 install flask-cors
WORKDIR /app
COPY api.py /app/api.py
EXPOSE 5252
CMD ["python3", "api.py"]