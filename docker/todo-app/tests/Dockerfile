FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/tests
ADD node_modules.tar.gz  ./todo-app/tests
COPY ./e2e ./todo-app/tests/e2e
CMD ["npm", "test"]