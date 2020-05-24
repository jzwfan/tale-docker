FROM java:8
MAINTAINER jzwfan "jzwfan@qq.com"

WORKDIR /data/tale
COPY ./source/ /data/tale/

RUN cd /data/tale

EXPOSE 9000

ENTRYPOINT ["java","-Xms256m","-Xmx256m","-Dfile.encoding=UTF-8","-jar","tale-latest.jar"]
CMD ["--app.env=prod",">/dev/null","2>&1"]



