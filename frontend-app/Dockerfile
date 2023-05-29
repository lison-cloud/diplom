FROM node
ENV KC_URL=http://localhost:8282
COPY package.json .
RUN npm install
COPY app.js .
COPY index.html .
COPY styles.css .
COPY client.js .
EXPOSE 8000
CMD [ "npm", "start" ]
