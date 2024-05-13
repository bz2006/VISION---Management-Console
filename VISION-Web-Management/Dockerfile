
FROM node:20
WORKDIR /VISION-Web-Management
COPY . .
RUN npm install 
RUN npm install bcrypt
CMD ["node", "server.mjs"]
EXPOSE 5001