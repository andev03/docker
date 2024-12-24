FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=study
ENV MONGODB_PASSWORD=kaka1342
ENV MONGODB_URL=cluster0.zd1bo.mongodb.net

CMD ["npm", "start"]