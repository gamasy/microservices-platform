FROM node:18-alpine

WORKDIR /app
COPY package*.json ./
RUN npm install --production

COPY src/ ./src/

EXPOSE 8080
USER node
CMD ["npm", "start"]
