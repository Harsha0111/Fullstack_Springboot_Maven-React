FROM node:16-alpine 
WORKDIR /app

COPY . .

EXPOSE 3000
RUN npm ci 
RUN npm run build

ENV NODE_ENV production

CMD [ "npx", "serve", "build" ]


# # Fetching the latest node image on alpine linux
# FROM node:alpine AS development

# # Declaring env
# ENV NODE_ENV development

# # Setting up the work directory
# WORKDIR /react-app

# # Installing dependencies
# COPY ./package.json /react-app
# RUN npm install

# # Copying all the files in our project
# COPY . .

# # Starting our application
# CMD npm start