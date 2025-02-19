# Using the official Node.js image
FROM node:14

# Setting the working directory
WORKDIR /app

# Copying package.json and package-lock.json into the container
COPY package*.json ./

# Installing dependencies
RUN npm install

# Copying the rest of the code
COPY . .

# Exposing the application port
EXPOSE 3000

# Running the application
CMD ["npm", "start"]
