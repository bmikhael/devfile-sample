FROM node:current-slim

WORKDIR /usr/src/app
COPY . .
RUN npm install

EXPOSE 4001
CMD [ "npm", "run", "console" ]
