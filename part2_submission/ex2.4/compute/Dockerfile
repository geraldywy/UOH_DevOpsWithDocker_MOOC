FROM node:25.6.0-bookworm

WORKDIR /usr/app

COPY . .

RUN npm ci

EXPOSE 3000

CMD ["node", "./index.js"] 