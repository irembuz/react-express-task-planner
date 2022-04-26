FROM node

RUN apt-get update

WORKDIR /task-planner

COPY public ./public
COPY src ./src
COPY package-lock.json .
COPY package.json .
COPY postcss.config.js /task-
COPY README.md .
COPY tailwind.config.js .
COPY tsconfig.json .

RUN npm install

CMD ["npm", "start"]
