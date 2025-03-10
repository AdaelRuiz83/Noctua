# Bienvenidos al proyecto Noctua

Este pequeño proyecto es para aprender a desarrollar un juego RPG para poder jugarlo en cualquier tipo de consola.

#Caracteristicas
    *Desarrollado en Phaserjs, Nodejs.
    *Temática retro.
    *La historia, la musica y el diseño lo estoy haciendo por mi cuenta.
    *En un futuro intentare hacerlo totalmente en linea.

#Estructura de carpetas
rpg-phaser-node/
│── server/                 # 📌 Carpeta del servidor
│   ├── server.js           # Archivo principal del servidor
│── public/                 # 📌 Carpeta para el juego (Phaser.js)
│   ├── index.html          # Página principal
│   ├── game.js             # Código del juego
│── src/                    # 📌 Código del juego en módulos
│   ├── scenes/             # Escenas del juego (menú, mapa, batalla, etc.)
│   │   ├── BootScene.js
│   │   ├── GameScene.js
│   │   ├── UIScene.js
│   ├── entities/           # Entidades del juego (jugadores, enemigos, NPCs)
│   │   ├── Player.js
│   │   ├── Enemy.js
│   ├── items/              # 📌 Información sobre los ítems del juego
│   │   ├── weapons.json
│   │   ├── potions.json
│── assets/                 # 📌 Contenido multimedia
│   ├── images/             # Imágenes y sprites
│   │   ├── characters/
│   │   ├── environment/
│   │   ├── items/
│   ├── audio/              # Música y efectos de sonido
│   │   ├── bgm/            # Música de fondo
│   │   ├── sfx/            # Efectos de sonido
│   ├── fonts/              # Tipografías personalizadas
│── package.json            # Configuración de Node.js
│── .gitignore              # Ignorar archivos innecesarios
