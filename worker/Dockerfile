FROM node:14.5.0-alpine3.10
WORKDIR /app
COPY ./package.json ./
RUN npm install
COPY . .
CMD ["npm","run","start"]