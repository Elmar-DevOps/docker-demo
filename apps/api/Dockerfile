FROM node:14-alpine

# EXPOSE 8080

WORKDIR /opt/app

ADD package*.json ./

RUN npm install

ADD . .

RUN npm run build api

CMD [ "node", "./dist/apps/api/main.js" ]

# WORKDIR /app

# COPY package*.json ./

# RUN npm install

# COPY . .

# RUN npm build

# CMD [ "npm", "start" ]
