FROM node

RUN apt-get update

WORKDIR /task-planner

COPY package.json .
COPY package-lock.json .

RUN npm install

COPY public ./public
COPY src ./src
COPY postcss.config.js /task-
COPY README.md .
COPY tailwind.config.js .
COPY tsconfig.json .

CMD ["npm", "start"]
