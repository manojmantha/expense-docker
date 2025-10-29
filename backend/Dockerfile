FROM node:20
WORKDIR /opt/bakend
COPY package.json .
COPY *.js .
RUN npm install
# ENV DB_HOST="mysql"
ENV DB_HOST="localhost"
CMD ["node", "index.js"]