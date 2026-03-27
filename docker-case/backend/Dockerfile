FROM node:18.16.0-alpine
WORKDIR /app
COPY package.json ./
RUN yarn install
COPY . .
RUN mkdir -p uploads
EXPOSE 8000
CMD ["yarn", "start"]
