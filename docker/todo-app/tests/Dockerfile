FROM mjgargani/puppeteer:trybe1.0 as BUILD
ENV FRONT_HOST todofrontend
ENV FRONT_PORT 3000
WORKDIR /
COPY . .
ADD node_modules.tar.gz ./
CMD [ "npm", "test" ]