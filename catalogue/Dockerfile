FROM node.js:20
WORKDIR /opt/suresh
COPY pakage.json .
COPY server.js .
RUN npm install
#    MONGO_URL="mongodb://mongodb:27017/catalogue"
ENV MONGO=true
ENV MONGO_URL="mongodb://mongodb:27017/catalogue"
CMD ["node", "app.js"]
CMD ["node", "app.js"]