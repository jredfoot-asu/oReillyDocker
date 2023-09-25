# syntax=docker/dockerfile:1
   
FROM node:18-alpine
ENV NODE_ENV=production
WORKDIR /app
COPY . .
RUN npm install --production
CMD ["node", "src/index.js"]
EXPOSE 3000