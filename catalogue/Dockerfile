FROM node:18
EXPOSE 8080
WORKDIR /opt/server/
ENV MONGO=true
copy package.json /opt/server/
copy server.js /opt/server/
RUN npm install
CMD ["node", "server.js"]



docker build -t cata:1.0.0



docker run -d --name cata cata:1.0.0  network 

docketr network