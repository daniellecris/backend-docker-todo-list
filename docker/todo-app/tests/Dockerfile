FROM mjgargani/puppeteer:trybe1.0
WORKDIR /
COPY package*.json ./
RUN npm install -s
COPY . .
CMD ["npm", "test"]
