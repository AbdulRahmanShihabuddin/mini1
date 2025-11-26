FROM node:14-alpine

WORKDIR /usr/src/app

# Install dependencies
COPY package*.json ./
RUN npm install --production

# Copy app source
COPY . .

EXPOSE 5000

ENV NODE_ENV=production

CMD ["npm", "start"]
