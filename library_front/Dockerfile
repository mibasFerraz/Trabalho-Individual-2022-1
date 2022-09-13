FROM node:alpine

#RUN pwd
WORKDIR /app

#COPY package.json /app/
COPY . .

RUN npm install --verbose

#COPY library_front /app

#USER node

CMD [ "npm", "start" ]

#RUN npm start

EXPOSE 3000
