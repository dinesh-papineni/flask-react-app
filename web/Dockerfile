FROM node:11.10.1-alpine

WORKDIR /app

ENV PATH /app/node_modules/.bin:$PATH
COPY package.json .
COPY package-lock.json .
RUN npm install


COPY . .

EXPOSE 8080
ENTRYPOINT [ "npm" ]
CMD [ "start" ]