FROM openjdk:8

RUN apt-get update \
  && yes | apt-get install postgresql-client docker-compose
CMD ["ila", "version"]
