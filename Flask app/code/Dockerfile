#Pull lighweight python image from DockerHub
FROM python:3.10-slim

#Setup working directory
WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

EXPOSE 8000

CMD ["python","app.py"]
