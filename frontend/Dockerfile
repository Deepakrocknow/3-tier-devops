FROM node:14
# WORKDIR /usr/src/app
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
CMD [ "npm", "start" ]
