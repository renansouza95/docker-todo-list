FROM node:14-alpine
WORKDIR /todo-app/front-end
ADD node_modules.tar.gz ./node_modules.tar.gz
COPY package*.json ./
COPY src ./src
COPY public ./public
RUN npm install
EXPOSE 3000
ENTRYPOINT ["npm", "start"]