FROM mjgargani/puppeteer:trybe1.0
ADD node_modules.tar.gz .
WORKDIR /usr/app 
COPY . .
RUN npm install
EXPOSE 3000
CMD ["npm", "test"]
