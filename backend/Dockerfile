FROM node

WORKDIR /app

COPY . .

# Install dependencies
RUN npm install

EXPOSE 5000

# Start the application
CMD [ "node", "index.js" ]