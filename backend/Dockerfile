FROM node:10.15.3-alpine
RUN mkdir -p /home/app
WORKDIR ./app
COPY . /home/app
RUN npm install
EXPOSE 8888
CMD ["server.js"]

