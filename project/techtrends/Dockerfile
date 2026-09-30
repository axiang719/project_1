FROM python:3.9-slim

WORKDIR /app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

EXPOSE 3111

CMD ["sh", "-c", "python init_db.py && python app.py"]
