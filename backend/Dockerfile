# use node img
FROM node:18

# set up work dir
WORKDIR /usr/src/app

# copy package.json and add dependecies
COPY package*.json ./
RUN npm install

# copy all code
COPY . .

#  API port 5000 for backend
EXPOSE 5000

# 运行后端服务器
CMD ["node", "index.js"]
