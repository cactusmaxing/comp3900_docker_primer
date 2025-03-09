FROM node:14
WORKDIR /usr/src/app
COPY package*.json ./
COPY . .
RUN npm install
RUN yarn install
EXPOSE 3000
CMD ["yarn", "start"]
