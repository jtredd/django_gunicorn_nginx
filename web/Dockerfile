FROM python:3.6

WORKDIR /srv/web/app

COPY requirements.txt /srv/web/app
RUN pip install --no-cache-dir -r requirements.txt
ADD ./web /srv/web/app
