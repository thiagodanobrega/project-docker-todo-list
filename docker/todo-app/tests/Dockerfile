FROM mjgargani/puppeteer:trybe1.0 AS build
ADD node_modules.tar.gz .
WORKDIR /usr/app 
COPY . .
RUN npm install
CMD ["npm", "test"]
