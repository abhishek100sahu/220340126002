FROM node:18-alpine3.14
LABEL maintainer="220340126002"
WORKDIR /usr/src/app
COPY sub.js /usr/src/app
RUN npm install npm@8.16.0 mqtt -g
CMD [ "node", "sub.js" ]