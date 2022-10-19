FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todotests
ADD node_modules.tar.gz .
COPY package.json .
COPY package-lock.json .
RUN npm install
COPY . .
CMD [ "npm", "test" ]

