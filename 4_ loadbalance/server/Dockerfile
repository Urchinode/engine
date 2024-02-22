FROM node:16
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8081
CMD [ "npm", "run", "start" ]

# docker build -t <IMAGE_NAME> .
# docker run -d -p <NGINX SERVER LISTEN PORT>:<DOCKER NODE.JS SERVER LISTEN PORT> --name snp server-nginx-practice