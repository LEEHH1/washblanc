FROM node:18

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

RUN npm run build

EXPOSE 4000

# 개발 모드로 실행으로 변경
CMD ["npm", "run", "start:dev"]