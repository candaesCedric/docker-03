FROM node

RUN mkdir /app
WORKDIR /app
COPY public/ ./public
COPY package*.json ./
RUN npm install
COPY src/ src/
EXPOSE 3000
CMD ["npm", "start"]
