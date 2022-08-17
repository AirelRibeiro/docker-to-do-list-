FROM node:14-alpine

WORKDIR /
ADD ./node_modules.tar.gz .
COPY . .

EXPOSE 3001

RUN npm install
ENTRYPOINT [ "npm", "start" ]