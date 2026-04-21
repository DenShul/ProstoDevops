FROM python:3.11-slim

WORKDIR /app

ENV APP_NAME="Backend"
ENV DB_PORT="5432"
ENV DB_HOST="localhost"

COPY app.py .

RUN chown -R 1001:1001 /app
USER 1001

EXPOSE 8080

CMD ["python", "app.py"]
