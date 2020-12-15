# base image
FROM node:12.2.0-alpine

# set working directory 
WORKDIR /app

# create react project
RUN npm install -g create-react-app

# add '/app/node_modules/.bin' to $PATH
ENV PATH /app/front/node_modules/.bin:$PATH
