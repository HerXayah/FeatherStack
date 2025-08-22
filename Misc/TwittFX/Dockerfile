FROM node:alpine
ENV NODE_ENV=production
ENV PORT=
WORKDIR /usr/app
COPY ./package.json ./
RUN npm install
CMD ["npm", "run", "deploy"]