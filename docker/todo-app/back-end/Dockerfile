FROM node:14-alpine
ADD node_modules.tar.gz .
WORKDIR /usr/app
COPY . .
RUN npm install
EXPOSE 3001
CMD ["npm", "start"]
