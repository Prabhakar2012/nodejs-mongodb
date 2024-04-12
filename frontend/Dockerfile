FROM node:14
WORKDIR /app
COPY package*.json .
RUN npm ci
RUN npx browserslist@latest --update-db
COPY . .
CMD ["npm", "start"]

