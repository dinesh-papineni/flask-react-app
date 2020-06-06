FROM python:3.7-alpine

WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

ENV PYTHONPATH=/app
EXPOSE 4433
ENTRYPOINT [ "python" ]
CMD ["__main__.py"]