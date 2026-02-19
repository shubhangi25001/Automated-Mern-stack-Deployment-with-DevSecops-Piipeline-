# Use Node.js LTS image
FROM node:18

# Set working directory
WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy all frontend source code
COPY . .

# Expose port 3000
EXPOSE 3000

# Start React app
CMD ["npm", "start"]
