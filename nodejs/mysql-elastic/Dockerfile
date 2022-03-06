FROM node:12-alpine
WORKDIR /usr/src/app
COPY . ./
RUN npm ci --only=production

CMD [ "node", "app.js" ]

