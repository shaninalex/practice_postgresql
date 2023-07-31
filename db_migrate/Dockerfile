FROM postgres:15.3

RUN apt-get install -y postgresql-client

WORKDIR /app

COPY . .

RUN chmod +x /app/migrate.sh

CMD ["/app/migrate.sh"]
