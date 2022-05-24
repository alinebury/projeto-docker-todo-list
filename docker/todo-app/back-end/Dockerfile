FROM node:14-alpine AS todobackend
WORKDIR /app
COPY . . 
ADD node_modules.tar.gz .
RUN npm install
EXPOSE 3001
ENTRYPOINT [ "npm start" ]
