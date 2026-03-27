FROM node:18.16.0-alpine
WORKDIR /app
COPY package.json ./
RUN yarn install
COPY . .
EXPOSE 4000
CMD ["yarn", "start"]
