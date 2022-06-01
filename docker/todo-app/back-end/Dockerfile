FROM node:14-alpine as BUILD
EXPOSE 3001
WORKDIR /
COPY . .
ADD node_modules.tar.gz ./
CMD ["npm", "start"] 
