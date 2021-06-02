<<<<<<< HEAD
FROM traefik:1.7.5-alpine

LABEL maintainer="Luis Coutinho <luis@luiscoutinho.pt>"

COPY traefik.toml acme.json /

RUN chmod 600 /acme.json
=======
FROM traefik:v2.2

LABEL maintainer="Luis Coutinho <luis@luiscoutinho.pt>"

WORKDIR /data

RUN touch acme.json

RUN chmod 600 acme.json

VOLUME /data
>>>>>>> 77be7c4001edfcd0d6b50f292ec7c43f64020d87
