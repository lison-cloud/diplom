FROM node
ENV KC_URL=http://localhost:8282
COPY package.json .
RUN npm install
COPY app.js .
COPY keycloak.json .
EXPOSE 5000
CMD [ "npm", "start" ]
