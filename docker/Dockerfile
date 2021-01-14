# Downloads the node package (version 14) into the image
FROM node:14

# Create app directory
WORKDIR SCA-Cloud-Project/

# Bundle app source
COPY . .

# Edit content of app.js
RUN sed -i 's/Welcome to SCA Cloud School Application/Welcome to SCA Cloud School Application, this is my first assessment/' app.js

# Opens port 1234
EXPOSE 1234

# Runs the command "node app.js"
CMD [ "node", "app.js" ]
