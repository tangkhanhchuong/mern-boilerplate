# Development
FROM node:10-alpine
WORKDIR /client
COPY package*.json /client/
RUN npm install
ADD . /client/
EXPOSE 3002
EXPOSE 35729
CMD ["npm", "start"]
