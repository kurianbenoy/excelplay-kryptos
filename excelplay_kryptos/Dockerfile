# FROM python:3.6
FROM python:3.6
 ENV PYTHONUNBUFFERED 1
 RUN mkdir -p /excelplay/excelplay_kryptos
 WORKDIR /excelplay/excelplay_kryptos
 ADD requirements.txt /excelplay/excelplay_kryptos
 RUN pip install -r requirements.txt
 ADD . /excelplay/excelplay_kryptos
