FROM node:16

EXPOSE 5000

WORKDIR /usr/src/app


COPY . .

RUN npm install

# RUN npm test

RUN npm run build

CMD ["npm", "run", "start-prod"]
