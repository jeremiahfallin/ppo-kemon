FROM node:alpine

COPY . .
COPY config/config-example.js config/config.js
RUN npm install
EXPOSE 8000
CMD ["node", "pokemon-showdown", "start", "--no-security"]