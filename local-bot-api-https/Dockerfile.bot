FROM node:16-slim@sha256:8e381b023efcf7a2fa4fb4e904ec9348d77bd3fc59f4551702db9aa52484082e

# Create app directory
WORKDIR /usr/src

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
COPY ./package*.json ./
RUN npm install

# Bundle app source
COPY . ./
