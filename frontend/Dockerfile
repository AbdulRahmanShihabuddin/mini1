FROM node:14-alpine

WORKDIR /usr/src/app

# Install dependencies
COPY package*.json ./
RUN npm install

# Copy app source
COPY . .

# Enable polling for file changes in containerized environments
ENV CHOKIDAR_USEPOLLING=true

EXPOSE 3000

CMD ["npm", "start"]
