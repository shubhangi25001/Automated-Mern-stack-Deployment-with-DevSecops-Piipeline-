# Use Node.js LTS image
FROM node:18

# Set working directory
WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy all backend source code
COPY . .

# Expose port 5000 (matches docker-compose)
EXPOSE 5000

# Start the backend server
CMD ["node", "server.js"]
