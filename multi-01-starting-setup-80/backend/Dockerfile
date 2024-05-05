FROM node
WORKDIR /app
COPY package.json .
RUN npm install
COPY . .
ENV MONGODB_USER=alive
ENV MONGODB_SECRET=kiwi
EXPOSE 80
CMD ["npm","start"]