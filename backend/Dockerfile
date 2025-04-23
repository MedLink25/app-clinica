FROM python:3.9-slim
WORKDIR /app
COPY . /app
RUN pip install fastapi uvicorn jinja2 pandas openpyxl pdfkit
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "80"]
