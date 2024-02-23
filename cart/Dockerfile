FROM node:18
EXPOSE 8080
WORKDIR /opt/server/
copy package.json /opt/server/
copy server.js /opt/server/
RUN npm install
CMD ["node", "server.js"]