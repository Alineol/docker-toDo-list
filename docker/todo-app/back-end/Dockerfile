FROM node:14-alpine as build
WORKDIR ./docker/todo-app/back-end/
COPY package*.json ./
RUN npm install 
COPY . .
EXPOSE 3001
CMD ["npm", "start"] 