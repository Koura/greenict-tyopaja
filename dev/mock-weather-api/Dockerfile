FROM node:18

WORKDIR /usr/src/app
ENV NODE_ENV=production

COPY src .
COPY package.json .
COPY package-lock.json .
COPY weather.sqlite .

RUN npm install

EXPOSE 8080
CMD ["node", "index.js"]
