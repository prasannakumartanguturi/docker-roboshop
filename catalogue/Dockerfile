

FROM node:20
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npm install
ENV mongo="true" \
    MONGO_URL="mongodb://mongodb:27017/catalogue" 
# command to run your application when the container starts
CMD ["node", "server.js"]