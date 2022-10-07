FROM node:latest
RUN mkdir /projects
RUN mkdir /www
COPY docker/docker-entrypoint.sh /
RUN chmod +x /docker-entrypoint.sh
WORKDIR /projects
RUN npm install --global astro
ENTRYPOINT '/bin/bash /docker-entrypoint.sh'