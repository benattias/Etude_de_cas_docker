FROM node:20-alpine
WORKDIR /src
COPY package*.json ./

ENV NODE_OPTIONS="--max-old-space-size=2048"
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "npm","start" ]
