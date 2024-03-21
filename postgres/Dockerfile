FROM postgres:15
LABEL maintainer='Filip Malinka <malinkaf@email.cz>'


COPY *.sql /docker-entrypoint-initdb.d/
COPY *.sh /docker-entrypoint-initdb.d/
