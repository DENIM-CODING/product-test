FROM node:18-alpine

# Create app directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application
COPY . .

# Expose the port your app runs on
EXPOSE 5001

# Command to run the application
CMD ["npm", "start"]