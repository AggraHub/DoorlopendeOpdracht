FROM node:17-alpine3.14
WORKDIR /home/zakaria/BaseApp/backend/
COPY *.js /home/zakaria/BaseApp/backend/
COPY package.json /home/zakaria/BaseApp/backend/.
RUN npm install
CMD ["node","index.js"]
EXPOSE 3000
