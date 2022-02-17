FROM alpine:3.14
WORKDIR /todo-app/back-end
COPY package.json, package-lock.json, ./
COPY src ./src
RUN npm install
EXPOSE 3001
ENTRYPOINT ["npm"]
CMD ["start"]