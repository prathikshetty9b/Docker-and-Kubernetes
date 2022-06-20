# Use existing image as base
FROM node:alpine

#Set the working directory
WORKDIR /usr/app

#Install node package manager
COPY ./package.json ./
RUN npm install
COPY ./ ./

#Start up Command
CMD [ "npm","start" ]
