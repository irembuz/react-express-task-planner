FROM node

RUN apt-get update

WORKDIR /task-planner

COPY package-lock.json .
COPY package.json .

RUN npm install

COPY bin ./bin
COPY public ./public
COPY routes ./routes
COPY views ./views
COPY app.js .
COPY README.md .

CMD ["npm", "start"]
