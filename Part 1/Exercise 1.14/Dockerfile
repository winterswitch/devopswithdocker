FROM node:16

WORKDIR /usr/src/app

EXPOSE 5000

COPY . .

RUN npm install && npm run build && npm install -g serve

CMD serve -s -l 5000 build
