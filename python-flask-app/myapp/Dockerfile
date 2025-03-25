FROM python:3.14-rc-slim-bookworm

WORKDIR /usr/src/myapp

COPY server.py requirements.txt ./

RUN pip install -r requirements.txt

EXPOSE 5000

CMD ["python", "server.py"]