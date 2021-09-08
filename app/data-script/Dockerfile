FROM alpine
RUN apk update && \
    apk add mysql-client

WORKDIR /opt

COPY import.sh ./
COPY mydatabase.sql ./

RUN chmod +x /opt/import.sh

CMD /opt/import.sh
