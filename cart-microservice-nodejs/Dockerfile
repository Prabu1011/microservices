FROM node:14
COPY . /var/www
WORKDIR /var/www
RUN rm package-lock.json
RUN npm init -y 
RUN npm install --package-lock

EXPOSE 1004

CMD [ "node", "index.js" ]
