FROM node:12-alpine
WORKDIR /cfm
COPY . .
RUN apk add --no-cache git
# npm install packages globally
# RUN npm install --global --unsafe-perm
EXPOSE 8080