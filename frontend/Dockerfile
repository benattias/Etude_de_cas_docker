
FROM node:20-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
ENV NODE_OPTIONS="--max-old-space-size=2048"
COPY . .
EXPOSE 3000
CMD ["npm", "run", "dev"]

