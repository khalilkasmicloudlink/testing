FROM 403344839207.dkr.ecr.us-west-2.amazonaws.com/node:latest
WORKDIR /app
COPY package*.json ./
RUN npm cache clean --force
RUN npm install
COPY . .
EXPOSE 3000
CMD ["npm", "run", "start"]