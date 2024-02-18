FROM node:latest
WORKDIR /usr/app
ENV NODE_ENV=development \
    CI=true
COPY . /usr/app/
RUN npm install \
    --loglevel verbose \
    --prefix . \
    --save .
CMD npm start