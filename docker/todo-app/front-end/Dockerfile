FROM node:14-alpine
WORKDIR /
COPY package*.json ./
RUN npm install -s
COPY . .
EXPOSE 3000
CMD ["npm", "start"]
