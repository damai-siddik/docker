FROM node:16-alpine

ENV PUBLIC_URL=http://localhost:3000

RUN mkdir /app

COPY . /app

RUN npm --cwd /app install

CMD ["npm", "--cwd", "./app", "run", "start"]