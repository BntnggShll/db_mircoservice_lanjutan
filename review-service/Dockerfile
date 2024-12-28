FROM python:3.9-slim
WORKDIR /app
COPY . /app
RUN pip install --no-cache-dir -r requirements.txt
RUN pip install flask-cors
EXPOSE 3003
CMD ["python", "app.py"]
