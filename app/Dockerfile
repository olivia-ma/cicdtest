FROM python:3.11-slim

WORKDIR /app
COPY requirements.txt .
RUN pip install --no-cache-dir -r ./app/requirements.txt

COPY . .
EXPOSE 8080

CMD ["python", "app/main.py"]