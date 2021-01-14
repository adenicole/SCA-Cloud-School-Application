# Downloads the node package (version 14) into the image
FROM node:14

# Create app directory
WORKDIR SCA-Cloud-Project/

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where available (npm@5+)
# COPY package*.json ./

# RUN npm install

#####################

# If you are building your code for production
# RUN npm ci --only=production

# Bundle app source
COPY . .

# Opens port 1234
EXPOSE 1234

# Runs the command "node app.js"
CMD [ "node", "app.js" ]
