# Dockerfile para el backend
FROM node:14

# Crear el directorio de la aplicación
WORKDIR /usr/src/app

# Copiar el package.json y package-lock.json
COPY package*.json ./

# Instalar dependencias
RUN npm install

# Copiar el resto del código
COPY . .

# Exponer el puerto
EXPOSE 3000

# Comando para ejecutar la aplicación
CMD ["node", "server.js"]
