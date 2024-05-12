FROM node:18

RUN npm install @angular/cli -g 

WORKDIR /app
COPY package.json .
COPY package-lock.json .
RUN npm install

COPY . .

ENV PATH /app/node_modules/.bin:$PATH
