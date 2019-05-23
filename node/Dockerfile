FROM node:10

WORKDIR /opt
COPY . .
WORKDIR /opt/app
RUN npm install

# code building for production
# RUN npm ci --only=production

EXPOSE 3000
CMD [ "npm", "start" ]

VOLUME /opt/app