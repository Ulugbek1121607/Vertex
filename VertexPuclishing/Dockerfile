FROM node:18

# Ishchi katalogni yaratish
WORKDIR /app

# Loyihadagi barcha fayllarni konteynerga nusxalash
COPY package*.json ./

# Kerakli modullarni o'rnatish
RUN npm install

# Loyihadagi kodlarni nusxalash
COPY . .

# Portni ochish
EXPOSE 3000

# Serverni ishga tushirish
CMD ["node", "server.js"]
