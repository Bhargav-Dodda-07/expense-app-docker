FROM node:20
EXPOSE 8080
WORKDIR /opt/server
COPY package.json .
COPY *.js .
ENV DB_HOST="mysql"
CMD ["node", "index.js"]