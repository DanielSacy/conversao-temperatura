FROM node:16.17.1
WORKDIR /app
COPY package*.json /app/
RUN npm install
COPY . /app/
CMD ["node", "server.js"]
