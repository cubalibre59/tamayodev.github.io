# TamayoDev - Chatbot GPT-4 avec Azure OpenAI

Ce projet est une application frontend intégrant un **chatbot alimenté par GPT-4**, déployé via **Azure OpenAI**.

## 🧠 Fonctionnalités

- Chatbox interactive basée sur **GPT-4**
- Connexion sécurisée à l'API Azure OpenAI
- Interface utilisateur moderne (HTML/CSS/JS ou framework si utilisé)
- Support pour l’historique de conversation *(optionnel)*

## 🚀 Technologies utilisées

- Azure OpenAI (GPT-4)
- JavaScript (ou framework : React, Angular, etc.)
- HTML/CSS
- Azure Portal & Ressources

## ⚙️ Configuration Azure

Avant de lancer l’application, vous devez :

1. Avoir un compte Azure avec accès à OpenAI
2. Créer une ressource Azure OpenAI
3. Récupérer :
   - **Endpoint** (URL de l'API)
   - **Clé API**
   - **Nom du déploiement**

## 🔐 Variables d’environnement (exemple)

Créez un fichier `.env` ou ajoutez vos variables dans votre config front :

```env
AZURE_OPENAI_ENDPOINT=https://votre-endpoint.openai.azure.com/
AZURE_OPENAI_KEY=xxxxxxxxxxxxxxxxxxxxxxxxxxx
AZURE_DEPLOYMENT_NAME=gpt-4-tamayodev
AZURE_API_VERSION=2024-05-01-preview





tamayodev/
├── index.html
├── chatbot.js
├── style.css
├── .env
└── README.md
