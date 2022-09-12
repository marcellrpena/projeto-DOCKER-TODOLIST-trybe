FROM node:14
WORKDIR /todo-app/back-end
ADD node_modules.tar.gz  ./todo-app/back-end
COPY ./src ./todo-app/back-end/src
EXPOSE 3001
CMD ["npm", "start"]