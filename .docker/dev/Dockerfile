FROM node:18

RUN npm i -g pnpm

WORKDIR /api
RUN cd /api

RUN apt update
RUN echo "alias ll='ls -alh'" > ~/.bashrc

CMD pnpm install && pnpm start:dev
