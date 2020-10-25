FROM python:3.8.3-slim

ADD requirements.txt /app/
WORKDIR /app/

RUN pip install -r requirements.txt

CMD ["uvicorn", "main:app", "--reload", "--host", "0.0.0.0", "--port", "8000"]
