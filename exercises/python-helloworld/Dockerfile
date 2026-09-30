FROM python:3.14.4
LABEL maintainer="Ax719"

COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt

CMD ["python", "app.py"]