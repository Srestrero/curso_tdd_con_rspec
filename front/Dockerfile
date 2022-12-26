FROM node:19.2-alpine
WORKDIR /front
COPY package*.json ./
RUN npm i axios
RUN npm install vuex@next --save
RUN yarn install
COPY . .
CMD ["yarn", "serve"]
