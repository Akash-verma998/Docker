FROM python:3.8-slim
WORKDIR /app
ADD . /app
RUN pip install -r requirements.txt
ENV NAME environment1
CMD ["python", "app.py"]