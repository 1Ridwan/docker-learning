FROM python:3.8-slim
WORKDIR /app
COPY . .
RUN pip install flask
EXPOSE 50002
CMD ["python", "app.py"]