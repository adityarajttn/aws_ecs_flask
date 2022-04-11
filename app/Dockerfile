FROM python:3.8

RUN mkdir /app
COPY app/app.py /app

WORKDIR /app

COPY common/requirements.txt  .
RUN pip install -r requirements.txt

ENTRYPOINT ["python"]

CMD ["app.py"]
