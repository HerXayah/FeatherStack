FROM node:alpine
ENV NODE_ENV=production
ENV PORT=80
WORKDIR /usr/app
COPY ./package.json ./
RUN npm install
RUN npm install wrangler
RUN npx wrangler login
CMD ["npm", "run", "deploy"]