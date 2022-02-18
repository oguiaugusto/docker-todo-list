FROM node:14-alpine
WORKDIR /
COPY . .
ADD ./node_modules.tar.gz ./
RUN npm install
EXPOSE 3001
ENTRYPOINT [ "npm", "start" ]