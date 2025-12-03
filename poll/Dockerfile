FROM python:3.13-alpine

WORKDIR /app


COPY . /app

RUN pip3 install --upgrade pip && \
    pip install --no-cache-dir -r requirements.txt
    
EXPOSE 80

CMD ["flask", "run", "--host=0.0.0.0", "--port=80"]
