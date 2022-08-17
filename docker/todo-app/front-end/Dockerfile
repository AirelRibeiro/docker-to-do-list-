FROM node:14-alpine

WORKDIR /
ADD ./node_modules.tar.gz .
COPY . .

EXPOSE 3000

RUN npm install
ENTRYPOINT [ "npm", "start" ]