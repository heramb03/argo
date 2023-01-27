FROM node:16
WORKDIR /usr/src/app
COPY package*.json .

ARG NAME

RUN npm i

COPY . .


EXPOSE 80
CMD ["node", "index.js"]
