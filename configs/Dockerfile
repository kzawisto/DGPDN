FROM python:3.5
ENV PYTHONUNBUFFERED 1
RUN mkdir -p /tmp
ADD requirements.txt /tmp/
RUN pip install -r /tmp/requirements.txt
RUN mkdir /workdir;
WORKDIR /workdir
