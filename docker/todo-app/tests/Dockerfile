FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/tests
ADD node_modules.tar.gz ./node_modules.tar.gz
COPY package*.json ./
COPY jest.config.js ./
COPY e2e ./e2e
RUN npm install
ENTRYPOINT ["npm", "test"]