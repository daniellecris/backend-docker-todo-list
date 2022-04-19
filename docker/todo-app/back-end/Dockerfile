FROM node:14-alpine

WORKDIR /

COPY package*.json ./

RUN npm install -s

COPY . .

EXPOSE 3001

CMD ["npm", "start"]
