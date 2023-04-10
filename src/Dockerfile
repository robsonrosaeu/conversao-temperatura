# Base image
FROM node:18.11.0

# Create app directory
WORKDIR /app

# Installing package
COPY package*.json ./

# Install app dependencies
RUN npm install

COPY . .

# Expose port 8080
EXPOSE 8080

# Start the application
CMD [ "node", "server.js" ]
