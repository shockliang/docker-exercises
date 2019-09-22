FROM node:alpine

WORKDIR /usr/app

# Copy package for npm install and cached.
COPY ./package.json ./
RUN npm install

# Copy all files to work dir.
COPY ./ ./

CMD ["npm", "start"]