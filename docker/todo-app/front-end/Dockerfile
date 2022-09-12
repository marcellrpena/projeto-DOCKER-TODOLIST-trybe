FROM node:14
WORKDIR /todo-app/front-end
ADD node_modules.tar.gz  ./todo-app/front-end
COPY ./src ./todo-app/front-end/src
EXPOSE 3000
CMD ["npm", "start"]