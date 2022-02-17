FROM alpine:3.14
WORKDIR /todo-app/front-end
COPY package.json, package-lock.json, ./
COPY src ./src
COPY public ./public
RUN npm install
EXPOSE 3000
ENTRYPOINT ["npm"]
CMD ["start"]