# Bot Discord Complet

Un bot Discord avec modération, musique et autres fonctionnalités.

## Installation

1. Clonez ou téléchargez ce projet.
2. Installez les dépendances : `npm install`
3. Créez un fichier `.env` avec votre token Discord, client ID et guild ID.
4. Exécutez `node deploy.js` pour enregistrer les commandes slash.
5. Lancez le bot : `npm start`

## Configuration

- `.env` : TOKEN, CLIENT_ID, GUILD_ID
- `config.json` : Préfixe, couleur des embeds, etc.

## Commandes

### Modération
- `/ban` : Bannir un utilisateur
- `/kick` : Expulser un utilisateur
- `/clear` : Supprimer des messages

### Musique
- `/play` : Jouer une musique
- `/skip` : Passer à la suivante
- `/stop` : Arrêter la musique
- `/queue` : Afficher la file

### Autres
- `/ping` : Test du bot

## Dépendances

- discord.js
- @discordjs/voice
- play-dl
- dotenv
- ffmpeg-static
