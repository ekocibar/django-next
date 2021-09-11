FROM node:alpine

# Create app directory
RUN mkdir -p /app/frontend
WORKDIR /app/frontend

# Install app dependencies
COPY package.json /app/frontend/
RUN npm install

COPY . /app/frontend

# Build application
RUN npm run build
CMD [ "npm", "dev" ]
