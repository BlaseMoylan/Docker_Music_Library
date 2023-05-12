FROM python:alpine3.17
WORKDIR /home/src/app
COPY requirements.txt ./
RUN pip install -r requirements.txt
COPY . .
EXPOSE 5000
