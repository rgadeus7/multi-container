# Use and existing docker image as base
FROM node:alpine
WORKDIR /app

#Download dependencies
COPY ./package.json ./
RUN npm install
COPY . .

#Tell the image on what to do when container starts
CMD [ "npm",  "run" ,"start"]         