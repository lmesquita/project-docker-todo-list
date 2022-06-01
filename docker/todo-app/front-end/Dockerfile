FROM node:14-alpine as BUILD
ENV  REACT_APP_API_HOST todo-backend
ENV REACT_APP_API_PORT 3001
EXPOSE 3000
WORKDIR /
COPY . .
ADD node_modules.tar.gz ./
CMD ["npm", "start"]
