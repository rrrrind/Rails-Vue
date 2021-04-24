FROM node:latest

WORKDIR /app/vue-project

RUN npm install -g @vue/cli

CMD ["/bin/bash"]

COPY ./vue-project/package*.json /app/
COPY ./vue-project/ /app/vue-project

