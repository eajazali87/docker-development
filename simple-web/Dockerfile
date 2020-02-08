# Use an existing docker image as base
FROM node:alpine

# Download and install a dependency
WORKDIR /usr/app
COPY ./ ./
RUN npm install

# Tell the image what to do when it starts as a container
CMD ["npm", "start"]