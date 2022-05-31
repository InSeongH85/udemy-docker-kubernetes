FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

# USE ENV 
ENV PORT 80

EXPOSE $PORT

#VOLUME [ "/app/node_modules" ]

CMD [ "npm", "start" ]