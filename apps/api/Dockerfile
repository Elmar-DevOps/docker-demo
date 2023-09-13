FROM node:14

EXPOSE 8080

WORKDIR /opt/app

ADD . .

RUN npm install

RUN npm build api

CMD [ "node", "./dist/apps/api/main.js" ]

# WORKDIR /app

# COPY package*.json ./

# RUN npm install

# COPY . .

# RUN npm build

# CMD [ "npm", "start" ]
