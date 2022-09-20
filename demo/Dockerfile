FROM python:latest
LABEL Maintainer="roni"
WORKDIR /usr/app/src

RUN pip install flask

COPY api.py ./
EXPOSE 80
CMD ["python", "api.py"]