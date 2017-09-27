FROM yxakuo/buildpack-deps:python-3.6_AP-library
# py3_ArticleProcess

MAINTAINER Allen tGuo(yxakuo@hotmail.com)

RUN mkdir /src
VOLUME /src
COPY /src/apps.py /src/
RUN chmod +x /src/apps.py
WORKDIR /src/

ENTRYPOINT ["python3"]
CMD ["apps.py"]