FROM python:3.14.0a1-slim

WORKDIR /app
COPY . ./

RUN pip install requests requests_oauthlib

ENTRYPOINT ["python", "/app/builder.py"]