FROM python:3

ADD ./apistar /user/src/app
WORKDIR /user/src/app

RUN pip install --no-cache-dir apistar==0.5.41 gunicorn

EXPOSE 8000
