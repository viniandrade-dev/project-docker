FROM node:14
EXPOSE 3001
ADD node_modules.tar.gz .
COPY package.json .
COPY package-lock.json .
RUN npm install
COPY . .
CMD [ "npm", "start" ]
