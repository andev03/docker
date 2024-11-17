FROM node

WORKDIR /app

COPY package.json .

RUN npm install -g nodemon

COPY . .

EXPOSE 80

CMD [ "npm", "start" ]