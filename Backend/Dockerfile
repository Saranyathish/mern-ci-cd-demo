# Use Node 18 image
FROM node:18

# Set working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy all backend files
COPY . .

# Expose port
EXPOSE 5000

# Start server
CMD ["npm", "start"]
