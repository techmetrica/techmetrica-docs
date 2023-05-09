# Specify the base image to use
FROM node:16-alpine

# Install pnpm
RUN npm install -g pnpm

# Set the working directory to /app
WORKDIR /app

# COPY package.json ./
COPY . .

# Install dependencies using pnpm
RUN pnpm install --only=production

# Expose port 49094
EXPOSE  49094

# Start the application
CMD ["pnpm", "start"]

