FROM node:14-alpine AS todofrontend
WORKDIR /app
COPY . . 
ADD node_modules.tar.gz .
RUN npm install
EXPOSE 3000
ENTRYPOINT [ "npm start" ]
