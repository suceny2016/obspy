FROM ubuntu:12.04

MAINTAINER Lion Krischer

# Can fail on occasion.
RUN apt-get update && apt-get upgrade || true
RUN apt-get -y install python-numpy python-scipy python-matplotlib python-sqlalchemy python-lxml python-mock python-mpltoolkits.basemap python-mpltoolkits.basemap-data python-pip python-tornado ttf-bitstream-vera python-decorator python-requests
RUN pip install future
RUN pip install https://github.com/Damgaard/PyImgur/archive/9ebd8bed9b3d0ae2797950876f5c1e64a560f7d8.zip
RUN echo "backend: agg" > /etc/matplotlibrc
