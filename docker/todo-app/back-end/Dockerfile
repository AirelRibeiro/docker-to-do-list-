FROM node:14-alpine

ADD ./node_modules.tar.gz /
COPY . /

EXPOSE 3001

ENTRYPOINT [ "npm", "start" ]