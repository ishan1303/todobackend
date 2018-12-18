FROM ishan1303/todobackend-base:latest
MAINTAINER Ishan Parmar <ishan.dx@gmail.com>

COPY target /wheelhouse

RUN . /appenv/bin/activate && \
    pip install --no-index -f /wheelhouse todobackend && \
    rm -rf /wheelhouse
