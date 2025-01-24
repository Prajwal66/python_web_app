FROM python:latest

WORKDIR /app

COPY requirements.txt /app/
COPY devops /app/


RUN pip3 install -r requirements.txt

SHELL ["/bin/bash", "-c"]

EXPOSE 8000

CMD ["python3","manage.py","runserver","0.0.0.0:8000"]



