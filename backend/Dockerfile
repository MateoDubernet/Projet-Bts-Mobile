FROM eclipse-temurin:17-jre-focal

# Dépendances minimales pour que Java puisse lancer un sketch Processing
RUN apt-get update && apt-get install -y \
    xvfb \
    libxrender1 \
    libxtst6 \
    libxi6 \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /app

# On copie l'export Linux
COPY ./app-export/ .

# On rend le script exécutable
RUN chmod +x ./backend

# Port du WebSocket
EXPOSE 8025

# On lance l'application à travers Xvfb (écran virtuel 1024x768x24)
CMD ["xvfb-run", "--auto-servernum", "--server-args=-screen 0 1024x768x24", "./backend"]