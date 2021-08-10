#FROM centos/python-36-centos7
FROM python:3.8-slim




COPY . /codigo

WORKDIR /codigo



RUN  pip install fastapi uvicorn       

CMD ["uvicorn", "main:app","--host", "0.0.0.0", "--port", "8000", "--reload"]
