FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD [ "npm", "start" ]

# docker run --name frontend -v $(pwd):/app -v /app/node_modules --rm  -p 3000:3000 -it nodes-frontend