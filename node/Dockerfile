FROM node:16.3.0


LABEL version="1.0"
LABEL description="This is the the docker image for Node API"
LABEL maintainer = ["abcd12345@gmail.com"]

WORKDIR /app

COPY . .

RUN ls
RUN npm install


EXPOSE 3000
EXPOSE 8080
EXPOSE 5000

CMD ["npm","run","start:dev"]
