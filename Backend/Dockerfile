# Use a Node.js base image
FROM node:16

# Set working directory
WORKDIR /usr/src/app

# Copy application files
COPY . .

# Install dependencies
RUN npm install

# Expose the application port
EXPOSE 3110

# Start the backend server
CMD ["node", "server.js"]

