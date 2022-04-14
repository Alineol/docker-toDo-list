FROM node:14-alpine as build
WORKDIR /docker/todo-app/front-end/
COPY package*.json ./
RUN npm install 
COPY . .
EXPOSE 3000
CMD ["npm", "start"] 
