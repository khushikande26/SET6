FROM python:3.10-slim

WORKDIR /app

COPY ../api/requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY ../api/app.py .
COPY ../api/utils.py .

EXPOSE 8000

CMD ["python", "app.py"]

