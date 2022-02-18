FROM node:14-alpine
WORKDIR /
COPY . .
ADD ./node_modules.tar.gz ./
RUN npm install
EXPOSE 3000
ENTRYPOINT [ "npm", "start" ]