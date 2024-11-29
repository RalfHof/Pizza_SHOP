# Verwende das Node.js-Image
FROM node

# Arbeitsverzeichnis festlegen
WORKDIR /app

# Package-Dateien kopieren und Abhängigkeiten installieren
COPY package.json ./

RUN npm install

# Quellcode kopieren
COPY . .

# Backend-Port offenlegen
EXPOSE 5030

# Anwendung starten
CMD ["npm", "start"]