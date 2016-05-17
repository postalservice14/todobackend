FROM postalservice14/todobackend-base:latest
MAINTAINER John Kelly <john.m.kelly@cdk.com>

COPY target /wheelhouse

RUN . /appenv/bin/activate && \
    pip install --no-index -f /wheelhouse todobackend && \
    rm -rf /wheelhouse
