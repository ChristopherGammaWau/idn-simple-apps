FROM node:18.16

WORKDIR /app

# Copy project contents into container
ADD . .

RUN npm install

EXPOSE 3000

CMD ["npm", "start"]