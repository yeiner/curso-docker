FROM node:12.16-alpine3.9
RUN mkdir -p /app
WORKDIR "/app"
COPY ./package*.json ./
RUN npm install
COPY . .
EXPOSE 3000/tcp
CMD ["npm", "run", "start"]