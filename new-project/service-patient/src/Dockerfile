FROM node:20-alpine
WORKDIR /app
COPY package.json ./
RUN npm install
COPY src/index.js ./
EXPOSE 5005
CMD ["node", "src/index.js"]