FROM node:20.18-alpine
RUN npm install -g @angular/cli@19
WORKDIR /usr/src/app
# COPY ./app/package*.json ./
# RUN npm install
# COPY ./app .
EXPOSE 4200
CMD ["npm", "start"]