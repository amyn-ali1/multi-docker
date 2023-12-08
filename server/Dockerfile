# use an existing docker image as base
FROM node:18-alpine

#work deroctory 
WORKDIR '/app'

#copy all the files to container
COPY ./package.json ./

#Download and install a dependency
RUN npm install

COPY ./ ./

#Tell the image what to do when it starts ad container
CMD [ "npm", "run" , "start" ]