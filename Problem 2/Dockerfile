FROM  node:13-alpine

#WORKDIR /usr/app

COPY . /usr/src/app/

#RUN apt update && install -y mysql\*

#RUN npm install

COPY . .

EXPOSE 3000

CMD [ "node","server.js" ]
