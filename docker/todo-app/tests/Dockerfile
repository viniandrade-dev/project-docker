FROM mjgargani/puppeteer:trybe1.0
ADD node_modules.tar.gz .
COPY package.json .
COPY package-lock.json .
RUN npm install
COPY . .
CMD [ "npm", "test" ]

