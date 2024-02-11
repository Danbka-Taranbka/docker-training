FROM node:16-alpine
WORKDIR /home/ilovedocker/app
COPY package*.json ./packages
RUN npm i
COPY . .
EXPOSE 3032
ENTRYPOINT ["node","./src/main.js"]
