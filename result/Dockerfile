FROM node:14

ENV PORT 80
EXPOSE 80

WORKDIR /usr/local/app

COPY package*.json /usr/local/app/

RUN npm install

COPY server.js /usr/local/app/

CMD [ "node", "server.js" ]
