#menggunakan node js versi 20
FROM node:20

WORKDIR /usr/src/app

COPY package*.json ./

# Install dependencies
RUN npm install

COPY . .

RUN npm run build

EXPOSE 3000


CMD ["node", "--max-old-space-size=200", "dist/main"]
