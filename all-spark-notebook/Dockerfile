FROM jupyter/all-spark-notebook:latest
MAINTAINER Sanghyun Lee <hammerha@gmail.com>

USER root
RUN apt-get update -y && \
  apt-get install -y xxd

RUN pip install bash_kernel; \
  python -m bash_kernel.install

