FROM yxakuo/buildpack-deps:py3_AP_library
# py3_ArticleProcess

MAINTAINER Allen tGuo


RUN mkdir /src
VOLUME /src
COPY /files/apps.py /src/
RUN chmod +x /src/apps.py
WORKDIR /src/

ENTRYPOINT ["python3"]
CMD ["apps.py"]