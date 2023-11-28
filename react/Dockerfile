FROM node:18.18.0


LABEL version="1.0"
LABEL description="This is the the docker image for react front end application"
LABEL maintainer = ["abcd12345@gmail.com"]

WORKDIR /app

COPY . .

RUN ls
RUN npm install

EXPOSE 3000

CMD ["npm","run","start"]
