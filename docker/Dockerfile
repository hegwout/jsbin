FROM node:12-alpine
RUN apk --no-cache add git

RUN git clone https://github.com/jsbin/jsbin.git /jsbin

WORKDIR /jsbin

RUN npm install -g grunt-cli
RUN npm install
RUN grunt build

ENV NODE_ENV=production

ENV PORT=8000
EXPOSE 8000

CMD node .