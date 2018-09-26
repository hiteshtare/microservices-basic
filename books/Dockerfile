#Base Image
FROM node:latest

#Copy all contents of '.' current directory to 'src' directory
COPY . /src

#Set working directory to 'src' as to run all the commands
WORKDIR /src

#Install npm dependencies
RUN npm install --production

#Expose the app on port 3000 so that other containers can interact with this container
EXPOSE 3000

#Start node app
CMD npm start