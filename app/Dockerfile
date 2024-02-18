# Build stage
FROM node:16 as build
WORKDIR /app
COPY package.json package-lock.json ./
RUN npm install
COPY . .
RUN npm run build

# Production stage
FROM nginx:stable-alpine as production
WORKDIR /usr/share/nginx/html
RUN rm -rf ./*
COPY --from=build /app/dist .
ENTRYPOINT ["nginx", "-g", "daemon off;"]
# docker build -t brainupgrade/buy-me-a-coffee-app .
# docker run -d -p 80:80 brainupgrade/buy-me-a-coffee-app

