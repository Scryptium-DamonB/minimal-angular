# Choose the Node.js version
FROM node:20

# Update the system
RUN apt-get update && apt-get upgrade -y

# Install Angular CLI globally in the container
RUN npm install -g @angular/cli

# Set the working directory
WORKDIR /workspace

# Add the "node_modules/.bin" to $PATH
ENV PATH /workspace/node_modules/.bin:$PATH