# syntax=docker/dockerfile:1
FROM node:12-alpine
RUN apk add --no-cache python2 g++ make
WORKDIR /ListingApp
COPY . .
RUN yarn install --production
CMD ["node", "src/index.js"]