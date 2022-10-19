FROM node:14-alpine
EXPOSE 3001
WORKDIR /todoback
ADD node_modules.tar.gz .
COPY package.json .
COPY package-lock.json .
RUN npm install
COPY . .
CMD [ "npm", "start" ]
