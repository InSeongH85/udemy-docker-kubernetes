FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80
# docker run 시 -v /app/node_modules 와 같다.
# VOLUME [ "/app/node_modules" ]

CMD [ "node", "server.js" ]