FROM node:13.12.0-alpine
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

COPY . .
RUN npm install
RUN npm install nodemon -g

EXPOSE 5000

CMD [ "npm", "run", "server" ]
