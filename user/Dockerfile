FROM node:20
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npm install
ENV mongo="true" \
    MONGO_URL=REDIS_URL='redis://redis:6379'
    Environment=MONGO_URL="mongodb://mongodb:27017/users"
# command to run your nodejs application and starts container 
CMD ["node", "server.js"]