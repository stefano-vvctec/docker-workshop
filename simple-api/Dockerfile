FROM node
COPY package.json .
RUN npm i
COPY app.js .
EXPOSE 3000
CMD ["node", "app.js"]