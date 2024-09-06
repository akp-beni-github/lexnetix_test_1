# base image: linux alpine/ node js frame work/ javascript runtime
FROM node:alpine

# create and set the working directory
WORKDIR /app

# copy package.json and lock json
COPY package*.json ./

# install dependencies
RUN npm install

# copy the rest of the application code (index.js and index.html)
COPY . .

# expose container port
EXPOSE 3000

# Start the application
CMD ["node", "index.js"]