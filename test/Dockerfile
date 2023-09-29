FROM debian:bullseye

RUN apt-get update && apt-get install -y \
		inetutils-ping \
		&& apt-get clean \
		&& rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

CMD ["ping", "8.8.8.8"]

