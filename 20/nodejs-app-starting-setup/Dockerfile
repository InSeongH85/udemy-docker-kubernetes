FROM node

WORKDIR /app

# package.json 파일을 복사 한 후 npm install 을 실행
# package.json 이 변경되었다면 이후 layer 는 재생성
COPY package.json /app

RUN npm install

COPY . /app

EXPOSE 80

CMD ["node", "server.js"]