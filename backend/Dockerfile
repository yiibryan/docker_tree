FROM node:10.15.3-alpine
RUN mkdir -p /home/app
WORKDIR /home/app
COPY ./app /home/app
RUN npm config set registry http://registry.npm.taobao.org/
RUN npm install
EXPOSE 3500
CMD [ "npm", "start" ]

