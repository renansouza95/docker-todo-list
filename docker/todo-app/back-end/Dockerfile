FROM node:14-alpine
WORKDIR /todo-app/back-end
ADD node_modules.tar.gz ./node_modules.tar.gz
COPY package*.json ./
COPY src ./src
RUN npm install
EXPOSE 3001
ENTRYPOINT ["npm", "start"]