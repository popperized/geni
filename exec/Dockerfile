FROM python:2.7-slim-jessie

RUN pip install --no-cache-dir geni-lib

COPY util.py /usr/local/lib/python2.7/site-packages/geni/

ENV PYTHONUNBUFFERED=on

ENTRYPOINT ["python"]
