FROM node:20.20.2-alpine3.22
EXPOSE 8080
COPY package.json .
COPY server.js .
RUN npm install
CMD ["node","server.js"]